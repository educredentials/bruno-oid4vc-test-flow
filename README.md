Based on the commit log, here's a draft for your README file:

---

# Bruno OID4VC Test Flow

This repository contains a collection for the Bruno REST client to test OpenID for Verifiable Credentials (OID4VC) flows.

## Introduction

Bruno is a REST client similar to Postman but simpler, cleaner, and open-source. You can learn more about Bruno at [usebruno.com](https://www.usebruno.com/).

This project holds a collection that allows us to test the issuance and importing of Verifiable Credentials, specifically of the "OpenBadges" type. The collection is a work in progress and does not yet fully adhere to the specifications.

## Features

### Credential Offer Retrieval

- A Credential Offer retrieval flow. The flow uses multiple calls and some business logic to retrieve (aka import) a credential. 


- [ ] It goes up to the authorization endpoint to test how to determine the endpoint and its capabilities where we should authorize to receive the credential from the offer. We'll need to configure and/or change the agent so it forces and uses the authorization.

### Issuance Endpoint

- Used to issue new credentials. This implementation is specific to the impierce unime-agent (aka ssi-agent) and does not adhere to any specific standard as the issuance of credentials is not described in a specification.

## Future Plans

- Make the collection adhere to the specifications by replacing hardcoded logic with dynamic paths.
- Ensure the agents used for testing offer the required features according to the spec.
- Simplify the business logic by creating libraries for signing and verifying credentials.

- 
## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.


---

Feel free to review and make any necessary edits or additions.
