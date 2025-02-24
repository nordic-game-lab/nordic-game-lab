# @nordic-game-lab/astro-gtm

This package allows you to quickly get Google Tag Manager running on your astro project

## Install

astro config
```javascript
import { defineConfig } from 'astro/config';

import GTM from "@nordic-game-lab/astro-gtm";

// https://astro.build/config
export default defineConfig({
  integrations: [GTM("GTM_Id", false)],
});
```
The first agrument in the GTM function is your GTM Id, and the second agrument is if you are using partytown.
