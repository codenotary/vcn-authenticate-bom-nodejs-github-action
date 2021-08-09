# vcn-authenticate-bom-nodejs-github-action

GitHub action that uses the **[vcn](https://github.com/codenotary/vcn)** tool from CodeNotary.com to authenticate the bill of materials (BoM) for [Node.js](https://nodejs.org) projects. It accepts _**package-lock.json**_ files (or directories containing such files) as input.

## How to use it

Have a look in the provided [example workflow](.github/workflows/example.yml).

:bulb: The underlying vcn Docker image can also be run directly (an example is also provided in the same [example workflow](.github/workflows/example.yml)). This way one can **specify any vcn** :boom: flag, not just the ones exposed by the GitHub action.

👉 [This link](https://github.com/marketplace?type=actions&query=publisher%3Acodenotary+) lists all the other GitHub actions that are available from CodeNotary.
