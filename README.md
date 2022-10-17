# Solid JS Wails

Wails Solid JS starter template

## Usage

1. Create a new wails project using this template by running
```sh
wails init -n my-solid-app -t https://github.com/sidwebworks/wails-solid-template
```

2. Before running `wails dev` command, you first need to install the frontend dependencies and generate the `frontend/dist` directory by running
```sh
cd frontend && pnpm install
```

```sh
pnpm build
```

then cd back into the root level of the project and run `wails dev`
  
You should see something like this,

![Wails demo image](https://user-images.githubusercontent.com/58144379/175643391-3d9e6488-d0c7-4f02-b330-bbc7ae225935.png)

## Building

To build a redistributable, production mode package, use `wails build`.
