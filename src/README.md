/// vite.config.js
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

export default defineConfig({
  plugins: [react()],
})

import {defineconfig} from 'v 
import react from '@vitejs/plug.
import mdx from 'mdx-js/rollup

export default defineconfig ({
    plugins: [
        { enforce: 'pre', ...mdx()
         react({ include: /\.(mdx|js
    ],
}) 

js importsource
 control wherewhere the jsx factory is imported from. Default to 'react'

   react ({ jsxImportsource: '@emot.

   js runtime option 
     react({ jsxRuntime: 'classic' }

     babel
     The babel option lets you add plugins, presets,and other configuration to the babel transformation performed on each included file.

     react({
        babel: {
            presets:[...],
            //your plugins run before,
            plugins:  [...] ,
            // use .babel src files
            babelrc: true;
            // use babel.config.js file:
             configFile: true 
        }
     })

     note: when not using plugins only esbuild is used for production builds resultung in faster builds.
     proposed syntax
      if you are using es syntax there are still in proposal status (eg. class properties), You can selectively enabel them with the babel.parser opts.plugins option.
           
           react({
            babel: {
                parseropts: {
                    plugins: ['decoration-leg]
                },
            },
           })
           this option does not enable code transformation. that is handled by esbuild.
           note: typescript syntax is handled automatically.

        middleware mode 
you should make sure your entry index.html file is transformed by vite.Here's an example for an express server:

                app.get('/' async(req,res, next)) => 
                try {
                    let html= fs.readfilesync(path.resolve{root,'index.html'), 'utf-8)

                    //transform html using vite plugins.
                    html= await viteserver.transformindex.html(req.url,html)

                    res.send(html)
                  } catch (e) {
                    return next(e)
                  }
                  })



                }


