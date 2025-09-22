# 04_Assignment-APIs_Bruseski
1. The open API I selected from the list was the first one, USGS Earthquake occurences.
2. The base URL of the USGS is https://earthquake.usgs.gov/fdnws/event/1/, the endpoint used is the query?format=geojson. The params used were that the format was geojson, the startime was starttime=2014-01-01 and the endtime was endtime=2014-01-02. No authentication required. Pagination includes FDSN event and the query supports the limit and offset parameters.
3. I basically just took the output folder, then set up the URL along side with requesting the raw file of the API, then saving the raw data with the JSON response then normalizing the JSON so i could save it to a Dataframe, once that was clean then I could save it to a CSV and then submit.
4. Some issues faced with this assignment was the certain URL to use and also the condensing of the API's, I used some of the examples within GitHub to help me as well.
   
