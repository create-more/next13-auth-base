# next13-auth-base

## Create Next 13 app



Configure paths in jsconfig.json
```
{
  "compilerOptions": {
    "baseUrl": "./src",
    "paths": {
      "@/components/*": ["components/*"],
      "@/app/*": ["app/*"]
   }
  }
}
```

## Update the NextJS Bootstrap

Styling SaaS

In src/app change global.css to .scss and change import in layout.js.

and delete .css imports in page.js. Change import

npm i sass@1.63.6
npm run dev