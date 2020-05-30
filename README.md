# Queue-Reporting-Framework
Report Queue Data after Processing in UiPath

<!-- wp:paragraph -->
<p>You must be wondering why we need to worry about this when we have Kibana + Elastic search enabled with UiPath Infrastructure, so we can straight away go and create Data Visualization ...</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>There could be other approach to report data such as storing the transactions logs or creating excel inside the process itself and send the report once the jobs finished.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Other way could be from Orchestrator, As the Information stored in queue items is displayed in Orchestrator, in the&nbsp;<strong>Transaction Details</strong>&nbsp;window, under&nbsp;<strong>Specific Data</strong>. Additionally, if the item failed and was retried, the history of the item is displayed in the same window.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>We can export all the transactions and information related to a given queue to a .csv file, by clicking the Export <strong>export_button </strong>button, in the Transactions page. All page filtering options apply to the generated file, too.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>But we took different Approach ...</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>We used Orchestrator API to get required Reports and send it to Business over email...It all depends on how you going to further use that export as input ...</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Alright !</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Lets see how we can use , Orchestrator API to Get Queue Data based on Filters &amp; Generate the report in required format.</p>
<!-- /wp:paragraph -->
