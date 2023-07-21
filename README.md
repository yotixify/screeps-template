# screeps-template
Basic template for the game screeps and pushing code using github actions


## Usage

To use this template simply put your javascript code under the ```src/``` folder and add your screeps API token to a secret in the github repository named ```token```. To add a secret follow the example here: [adding a github secret to a repository](https://docs.github.com/en/actions/security-guides/encrypted-secrets)

Whenever a code change is merged or pushed to the main branch it will deploy that code to screeps. 