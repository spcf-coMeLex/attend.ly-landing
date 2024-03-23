# Deployed Canister URL

```
https://mphur-2iaaa-aaaal-qdkbq-cai.icp0.io/
```

# Initializing DFX

Run dfx in separate terminal

```
dfx start --clean
```

# Configuring dfx.json

```
{
    "canisters": {
      "vanilla-icp": {
        "frontend": {
          "entrypoint": "src/index.html"
        },
        "source": ["src"],
        "type": "assets"
      }
    },
    "dfx": "0.17.0",
    "version": 1
  }
```

# Deploying your landing page (frontend)

Open VS Code and open a terminal instance and run:

```
dfx deploy
```
