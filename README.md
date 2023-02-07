# Welcome to the Delegate Registry!

In this repository, we aim to create a comprehensive directory of individuals and organizations in the [Substrate](https://substrate.io) ecosystem to share their delegators' information in the [Nova Wallet](https://novawallet.io/)

## How it looks like

Here are a few examples of what your information could look like in the directory:

<details>
  <summary>Nova Wallet app screens</summary>

<img src="https://i.ibb.co/TL35ZWn/Screenshot-2023-02-07-at-11-12-21.png" width="100">
<img src="https://i.ibb.co/3RzBqb1/Screenshot-2023-02-07-at-11-14-00.png" width="100">
<img src="https://i.ibb.co/XDZNBt4/Screenshot-2023-02-07-at-11-14-03.png" width="100">
<img src="https://i.ibb.co/HB5544w/Screenshot-2023-02-07-at-11-14-06.png" width="100">

</details>


Note: These are just examples and the actual format may vary.


## Sharing your information

To share your information, please create a JSON file with the following format:

```json
{
    "address": "substrate address in ss58 format",
    "name": "name",
    "image": "link to image",
    "shortDescription": "short string no more than 256 chars",
    "longDescription": "string, support markdown",
    "isOrganization": "bool"
}
```


- `address`: Your Substrate address in [ss58 format](https://substrate.dev/docs/en/learn/address-format).
- `name`: Your name or the name of your organization.
- `image`: A link to an image that represents you or your organization.
- `shortDescription`: A short description of yourself or your organization (no more than 256 characters).
- `longDescription`: A more detailed description of yourself or your organization, which can include markdown syntax for formatting.
- `isOrganization`: A boolean value indicating whether you are an individual or an organization.

## Pull requests

Please submit your information as a pull request to this repository. We will review your submission and add it to the directory once approved.

## Directory

A list of networks with information about individuals and organizations in the Substrate ecosystem can be found [here](./registry).
