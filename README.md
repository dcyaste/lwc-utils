# LWC Service Modules

Rewrite of [Service Components Framework (Aura)](https://github.com/tsalb/sfdc-lightning-service-components) but with Lightning Web Components (LWC). This repository includes all my previous Service Components for easy side-by-side comparison.

![side-by-side](/readme-images/side-by-side.png?raw=true)

## Install with SFDX

SFDX CLI and VSCode has matured enough for general usage so I will be moving my repo to SFDX format only.

For VSCode and SFDX setup see steps (1 and 2) from the [official lwc-recipes repo](https://github.com/trailheadapps/lwc-recipes#installing-recipes-using-salesforce-dx). Once you have the SFDX CLI set up and Authed into a Dev Hub you can then:

1) Open VSCode, then open terminal with `` ctrl+` `` then clone lwc-utils.

```
git clone https://github.com/tsalb/lwc-utils
```

2) Use [Command Palette](https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette) to `SFDX: Create a Default Scratch Org` .

3) Use Command Palette to `SFDX: Push Source to Default Scratch Org`.

4) Use Command Pellete to `SFDX: Open Default Org`.

## Install with unlocked package

Coming later (maybe)...

## Service Components Framework (Aura)

See [Readme](https://github.com/tsalb/sfdc-lightning-service-components#dataservice-usage-example) for any Aura component usage.

## Datatable Service (LWC)

Right now there is a sample using `@wire` with a reactive attribute. Parent relationships (1 level up) are working okay. It's safer to use formulas still, for now.

It's possible to call this LWC service module with `async await` but that will be coming later.

![side-by-side](/readme-images/datatable.gif?raw=true)


