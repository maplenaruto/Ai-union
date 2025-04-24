# Ai-union

open the website
[Union Ceremony](https://ceremony.union.build/)

follow the steps in the website, and use the code:

mkdir -p ceremony && sudo docker pull ghcr.io/unionlabs/union/mpc-client:latest && sudo docker run -v $(pwd)/ceremony:/ceremony -w /ceremony -p 4919:4919 --rm -it ghcr.io/unionlabs/union/mpc-client:latest

then, open the website:
[Union Dashboard](https://dashboard.union.build/achievements)
