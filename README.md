# About
My personal homepage, built entirely in [SvelteKit](https://kit.svelte.dev/).
[![Better Stack Badge](https://uptime.betterstack.com/status-badges/v3/monitor/w05i.svg)](https://uptime.betterstack.com/?utm_source=status_badge)

# Building
If you're interested in building it, first, ensure you have all dependencies:  
(I use pnpm, but you could substitute it for npm)  
```
pnpm install
```
Make any changes. Then, when it's time to build, run:  
```
pnpm build
```
## Static
Your output is the `build` folder now located in the current directory. Serve this with your web server, or however else you serve static files.  
I use [caddy](https://caddyserver.com/). Here is an example configuration that can be done with a stock build of caddy:  
```
https://www.hashg.xyz {
        root * /my/project/path/build
        file_server {
                precompressed br gzip
        }
}
```
## Node
You can configure svelte to build the site for use with Node: https://kit.svelte.dev/docs/adapter-node
