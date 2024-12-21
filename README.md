# My Day Looks like  `Saturday`
## Words Talks Facts Screams  `Warmup liner`

Today the weather is very *gloomy* and _rainy_   `Mohsam`

I feel like **felicia** today  `Kicker`

## Below are the checklist for the day  `workflow`
+ follow the money
+ gain some tech skills
+ love mother and nature
+ build some muscles

## Each activity will have actions like `Apply`
+ follow the money
  - look for some mutual funds to invest.
+ gain some tech skills
  - read about Containerization ( API Interaction )
+ love mother and nature
  - help in cooking and water the plants
+ build some muscles
  - Hit tricep & obliques
 
## Coding Language for the day
```bicep
resource containerappjob 'Microsoft.App/managedEnvironments@2022-11-01-preview' = {
  name: ceJobLibName
  location: cajobLibRegion
  identity: {
    type: 'SystemAssigned'
  }
  properties: {
    appLogsConfiguration: {
      destination: 'log-analytics'
      logAnalyticsConfiguration: {
        customerId: reference(logAnalyticsWorkspaceId, '2020-08-01').customerId
        sharedKey: listKeys(logAnalyticsWorkspaceId, '2020-08-01').primarySharedKey
      }
    }
  }
}
```
 
## Favorite social media platform
[ X / Twitter ](https://x.com/home)

## My personality pick today
![BOB MARLEY](https://github.com/Debjyoti30/github-foundation-learning/blob/main/OIP.jpg)
