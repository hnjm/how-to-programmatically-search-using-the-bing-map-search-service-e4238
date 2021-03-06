<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/DXMapExample/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DXMapExample/MainWindow.xaml))**
* [MainWindow.xaml.cs](./CS/DXMapExample/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/DXMapExample/MainWindow.xaml.vb))
<!-- default file list end -->
# How to  programmatically search using the Bing Map Search service


<p>This example demonstrates how to create a custom search panel that searches for location, keywords and other parameters using the  <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapBingSearchDataProvider_Searchtopic"><u>BingSearchDataProvider.Search</u></a> method.</p><p>To start using the Search panel,  specify search parameters (location, keyword, start search index, geographical point coordinates) in the textbox elements. </p><p>When you handle the <strong>sear</strong><strong>ch</strong><strong>_Click </strong>event, all parameters are passed to the<strong> Search</strong><strong> </strong><strong> </strong>method, and you can see the result in the textblock element below. </p><p>The  results contain a  <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapLocationInformation_DisplayNametopic"><u>display name</u></a> , <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapLocationInformation_EntityTypetopic"><u>entity type</u></a> and   <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapLocationInformation_Addresstopic"><u>address</u></a> associated with the search  <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapSearchRequestResult_Locationtopic"><u>location</u></a>.  In addition,  the <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapSearchRequestResult_AlternateSearchRegionstopic"><u>SearchRequestResult.AlternateSearchRegions</u></a>  property returns results of searching alternate regions. </p><p>Moreover, you can see  search request  information  returned by the <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapRequestResultBase_ResultCodetopic"><u>RequestResultBase.ResultCode</u></a>, <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapRequestResultBase_FaultReasontopic"><u>RequestResultBase.FaultReason</u></a> and  <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapSearchRequestResult_EstimatedMatchestopic"><u>SearchRequestResult.EstimatedMatches</u></a> properties. </p><p>Note that if you run this sample as is, you will get a warning message saying that the specified Bing Maps key is invalid. To learn more about Bing Map keys, please refer to the <a href="http://documentation.devexpress.com/#WPF/CustomDocument10974"><u>How to: Get a Bing Maps Key</u></a>  tutorial.</p>


<h3>Description</h3>

<p>This example demonstrates how to create a custom search panel that searches for location, keywords and other parameters using the <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapBingSearchDataProvider_Searchtopic"><u>BingSearchDataProvider.Search</u></a> method.</p>
<p>To start using the Search panel, specify search keyword in the textbox element.</p>
<p>When you handle the <strong>sear</strong><strong>ch</strong><strong>_Click </strong>event, all parameters are passed to the<strong> Search</strong> method, and you can see the result in the text block element below.</p>

<br/>


