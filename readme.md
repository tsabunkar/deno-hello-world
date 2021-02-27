# DENO

### Installation

- $ curl -fsSL https://deno.land/x/install/install.sh | sh
- (installed in --> /home/tejas/.deno/bin)
- $ /home/tejas/.deno/bin/deno --help (Help)
- (To set deno variable)
  - $ export DENO_INSTALL="/home/tejas/.deno"
  - $ export PATH="$DENO_INSTALL/bin:$PATH"

## Run Helloworld

- $ deno run https://deno.land/std/examples/welcome.ts


## VSCode Extension

- Marketplace : vscode-deno or Deno by denoland

## Hello-world

- create file- hello-world.ts
- \$ deno run --allow-net hello-world.ts
- Visit website : http://localhost:8000/