<div align="center">
  <img src="https://raw.githubusercontent.com/VueServerRenderer/VueServerRenderer/main/lzyaemujz884m4tggslk.webp" width="200" alt="logo"/>
</div>

# deno vue-server-renderer

This package offers deno server-side rendering

A vue server renderer like (https://www.npmjs.com/package/vue-server-renderer) but for deno. 

# Quick Start

## Example Demo

import vueServerRenderer from 'https://deno.land/x/vue_server_renderer@1.0.1/mod.js'


vueServerRenderer(App, (err:any, res:any) => {
        console.log('result', res); 
        console.log('error', err);
        //print(res);
        rendered = res;
      });




