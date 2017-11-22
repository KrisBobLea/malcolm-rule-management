#Malcolm Rules Editor

**What is Malcolm Rules?**

 Malcolm Rules is a complex rules description structure base on Json.
 
 **features:**
 
1.unlimited group

2.unlimited level

3.unlimited restriction
 
**How about Malcolm Rules Json looks like?**

```
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
