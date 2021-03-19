    The app developed is an informative app which shows the various statistics about Covid-19 in different countries with graphical respresentation (Pie chart, Bar chart, Line chart). When a particular country is searched for, the statistics and graphs change according to that country.
    
    I've used the JSON data file - https://disease.sh/v3/covid-19/countries
    
    The following libraries were used in plotting the graphs by fetching data from the online JSON data file.
   
    // card view library
    implementation 'androidx.cardview:cardview:1.0.0'

    // BlackFizz Chart Library
    implementation 'com.github.blackfizz:eazegraph:1.2.5l@aar'
    implementation 'com.nineoldandroids:library:2.4.0'

    // volley libraryfor getting response from REST api.
    implementation 'com.android.volley:volley:1.1.1'

    // Arc loader library
    implementation 'com.leo.simplearcloader:simplearcloader:1.0.+'
    
    Among many libraries, I chose to work with these as they were very much easier to handle according to my convenience. The other reasons why I chose them are listed below:
    1. eazegraph is an Android library for creating fancy charts. Its a lighweight library which is easy-to-use and its highly customizeable.
    2. Volley is an HTTP library that makes networking for Android apps easier and most importantly, faster.
    
    
