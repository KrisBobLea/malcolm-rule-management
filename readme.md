# Malcolm Rules Editor

## What is Malcolm Rules?

 Malcolm Rules is a complex rules description structure based on Json.

###  Features:
 
- Unlimited group

- Unlimited level

- Unlimited restriction

### Scenes to be used
Risk control, online activities, points issued and other systems need to flexibly configure the complex rules.

## How about Malcolm Rules Json looks like?

```json
{
    "type": "subrules",
    "logic": "and",
    "subrules": [
        {
            "type": "restriction",
             //your business properties
        },
        {
            "type": "subrules",
            "logic": "or",
            "subrules": [
                {
                    "type": "restriction",
                    //your business properties
                },
                {
                    "type": "restriction",
                    //your business properties
                }
            ]
        }
    ]
}
```
## Why named Malcolm Rule Structure?
Because of the band AC\DC's guitarist Malcolm Young.

## How to use this editor?
This editor just is a example, you need merge this code to your project.


## Web Editor UI

![web ui](malcolm-rule-web-editor/assets/ui.png)