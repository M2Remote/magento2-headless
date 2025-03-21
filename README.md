# magento Open Source/Adobe Commerce headless Version
> Application is not responsible for rendering the end page to the user, but provide the data over network connection via REST API/GraphQL.So any frontend technologies can be used with application

## supported almost every frontend which can consume REST API/GRAPHQL 
- VUESTOREFRONT/Alokai (https://github.com/vuestorefront/mage2vuestorefront | https://github.com/vuestorefront/magento2) [VUE JS]
- GRAPHCOMMERCE (https://www.graphcommerce.org) [REACT JS]
- PWA Studio by Adobe Commerce [REACT JS]
- Gatsby (https://github.com/gatsbyjs/gatsby) [NEXT JS]
- SVELTE COMMERCE (https://github.com/itswadesh/svelte-commerce) [svelte]
- SVELTE COMMERCE open-source Sveltekit Tailwind (https://github.com/martykuentzel/sveltekit-tailwind-ecommerce) [svelte]
- Daffodil (https://next.daff.io/) [Angular]
- Front-Commerce (www.front-commerce.com) [REACT]
- Go PWA (https://www.gomage.com/magento-2-pwa/storefront)
- Rapidez (https://rapidez.io/) [vue]
- Storefront X (https://www.storefrontx.io/)
- React Storefront (https://www.reactstorefront.io/)
- Adyen Vuejs (https://github.com/adyen-examples/magento-headless-demo) 

## examples
Eleganza: Magento + PWA Studio
Zadig & Voltaire: Magento + Vue Storefront magento 2


## strategies are listed below:
- Building a framework -
    - Frontend rendering is removed from Magento 2, and the front-end is entirely handled by a headless framework (React, Vue, Next.js, etc.).
    - Magento APIs (GraphQL or REST) serve as the communication layer between the back-end (Magento 2) and the front-end.
    - Custom API Endpoints (optional) can be added for additional features.
    - Authentication and security are handled via Bearer Tokens or OAuth for API access.
    -  Removing frontend rendering 
    -  Redirect to admin Panel (backend) using server configuration
  
