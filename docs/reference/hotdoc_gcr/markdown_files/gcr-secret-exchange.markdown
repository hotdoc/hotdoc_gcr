### GcrSecretExchange

Exchange secrets between processes in an unexposed way.

 Allows exchange of secrets between two processes on the same system without
 exposing those secrets to things like loggers, non-pageable memory etc.

 This does not protect against active attacks like MITM attacks.

 Each side creates a [](GcrSecretExchange) object, and one of the sides calls
 [](gcr_secret_exchange_begin). This creates a string, which should be passed
 to the other side. Each side passes the strings it receives into
 [](gcr_secret_exchange_receive).

 In order to send a reply (either with or without a secret) use
 [](gcr_secret_exchange_send). A side must have had [](gcr_secret_exchange_receive)
 successfully called before it can use [](gcr_secret_exchange_send).

 The [](GcrSecretExchange) objects can be used for multiple iterations of the
 conversation, or for just one request/reply. The only limitation being that
 the initial request cannot contain a secret.

 Caveat: Information about the approximate length (rounded up to the nearest
 16 bytes) may be leaked. If this is considered inacceptable, do not use
 [](GcrSecretExchange).

* [GcrSecretExchange]()
* [gcr_secret_exchange_get_protocol]()
* [gcr_secret_exchange_new]()
* [GCR_SECRET_EXCHANGE_PROTOCOL_1]()
* [gcr_secret_exchange_send]()
* [GcrSecretExchangeClass]()
* [gcr_secret_exchange_receive]()
* [gcr_secret_exchange_begin]()
* [gcr_secret_exchange_get_secret]()
