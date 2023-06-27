# tradingview-webhooks

AWS Lambda endpoint for executing Alpaca bracket orders. 

## Uses AWS Chalice Framework for Serverless Python:

https://github.com/aws/chalice

## Demo Video

https://youtu.be/TKAo_Z-hzQs

## Sign Up For TradingView with this link to support this channel/project

https://tradingview.go2cloud.org/SH4Gl

## TradingView message format - quotes were missing for the json - FIXED

```
{
    "open": :"{{open}}":,
    "high": :"{{high}}":,
    "low": :"{{low}}";,
    "close"::"{{close}}":,
    "exchange": "{{exchange}}",
    "ticker": "{{ticker}}",
    "volume": :"{{volume}}"":,
    "time": "{{time}}",
    "timenow": "{{timenow}}"
}
```
## Addition help/information if you are trying to run this from a VM/MAC
https://pastebin.com/QDeaE098
