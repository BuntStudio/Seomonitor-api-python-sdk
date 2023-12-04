# ForecastConfiguration

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**timeframe** | **str** | The duration of the scenario in months. | [optional] 
**start_month** | **str** | The month and year when the scenario was set to start. | [optional] 
**extended_forecast** | **bool** | Whether the projection includes the extended forecast timeframe and the results estimated for it. | [optional] 
**target_rank_range** | **bool** | Whether the target rank range option is enabled for the Objective. If &#x27;true&#x27;, the estimated results of the forecast will be returned for both the lower (worst) and the higher (best) target. | [optional] 
**progression_speed** | **str** | The user-configured speed at which the average selected target rank will be reached.  Possible values are &#x60;conservative&#x60;, &#x60;mostly conservative&#x60;, &#x60;moderate&#x60;, &#x60;mostly moderate&#x60;, &#x60;optimistic&#x60;, &#x60;mostly optimistic&#x60;, and &#x60;custom&#x60;. | [optional] 
**use_year_over_year** | **bool** | Whether the option to include the Year-over-Year search trends of the keywords in the forecast calculation is enabled. | [optional] 
**use_search_volume_by_device** | **bool** | Whether the option to include the search volume for each device of the keywords in the forecast calculation is enabled. | [optional] 
**use_long_tail_effect** | **bool** | Whether the option to include the estimation of additional traffic generated by other keywords semantically related to the ones included in the forecast is enabled. | [optional] 
**use_percentage_clicks** | **bool** | Whether the option to include the Percentage Clicks metric in the forecast calculation is enabled. | [optional] 
**conversion_data** | [**ForecastConfigConversionData**](ForecastConfigConversionData.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
