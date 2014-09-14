ForecastIOMono
==============

ForecastIOMono - Based off of C# Wrapper https://github.com/f0xy/forecast.io-csharp

Works with Mono projects, including Xamarin.IOS, Xamarin.Android and Xamarin.Mac. 

Usage:

var ForecastRequest = new ForecastIORequest("[apikey]",[lat],[lon],[unit]);

ForecastIOREsponse Response = ForecastRequest.Get();

