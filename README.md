## Running React on Repl.it

[React](https://reactjs.org/) is a popular JavaScript library for building user interfaces.

[Vite](https://vitejs.dev/) is a blazing fast frontend build tool that includes features like Hot Module Reloading (HMR), optimized builds, and TypeScript support out of the box.

Using the two in conjunction is one of the fastest ways to build a web app.

### Getting Started
- Hit run
- Edit [App.jsx](#src/App.jsx) and watch it live update!

By default, Replit runs the `dev` script, but you can configure it by changing the `run` field in the `.replit` file.

https://docs.metamask.io/guide/ethereum-provider.html#methods  
https://docs.metamask.io/guide/rpc-api.html#table-of-contents


###exemple call
const balance = await ethereum.request({ method: "eth_getBalance", params:['0x858077f49b961ef27b0b09313bedfe33aca0ca44',"latest"] });

###ethers js  
https://docs.ethers.io/v5/api/providers/  
https://docs.ethers.io/v5/api/providers/provider/#Provider-getBalance
