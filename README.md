# Ai-union

open the website
[Union Ceremony](https://ceremony.union.build/)

You must have docker installed and running in order to contribute. Once you have docker running, copy the following command in your terminal:

---

mkdir -p ceremony && docker pull ghcr.io/unionlabs/union/mpc-client:v1.2 && docker run -v $(pwd)/ceremony:/ceremony -w /ceremony -p 4919:4919 --rm -it ghcr.io/unionlabs/union/mpc-client:v1.2

---


then, open the website:
[Union Dashboard](https://dashboard.union.build/achievements)
