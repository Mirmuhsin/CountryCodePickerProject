Country Code Picker Library
===========================

If you are looking for an android library for Country Selector or Country Spinner or Country Phone Code selector, this is the perfect place for you.

Country Code Picker (CCP) <img src="https://farm6.staticflickr.com/5726/30960801342_6e65c7ddd5_m.jpg" width="100"> or
<img src="https://farm5.staticflickr.com/4468/23591251898_f8c5e8393a_b.jpg" width="230">
  is an android library which provides an easy way to search and select country or country phone code for the telephone number.
  
  ![AwesomeCCPLIbrary](https://i.makeagif.com/media/10-02-2017/RyO2k_.gif)

Introduction
------------
* Give a professional touch to your well designed form like login screen, sign up screen, edit profile screen with CCP. When used as phone code picker, it helps by removing confusion about how to add phone number and making view more understandable. 
	  
* With CCP you can get following views easily without boilerplate code. (Left: Phone code selector. Right: Country Selector)

    - <img src="https://farm6.staticflickr.com/5625/30296514763_e3af239e2c_z.jpg" width="300">     <img src="https://farm5.staticflickr.com/4343/23591138638_45d0f08daf_b.jpg" width="400">    
    
* Tapping on CCP will open a dialog to search and select country (Left: Phone code selector. Right: Country Selector)
    - <img src="https://farm6.staticflickr.com/5686/30982885732_9e91ede573_b.jpg" width="300"> <img src="https://farm5.staticflickr.com/4384/37440899521_d19781dc52_b.jpg" width="300">

How to add to your project
--------------

Add this to your gradle file and sync

  ````groovy
          dependencies {
            implementation 'com.hbb20:ccp:2.2.0'
          }
   ````

  What's new?
  > - Swedish language support
  > - Feature to exclude specific countries from the list. [Wiki Page](https://github.com/hbb20/CountryCodePickerProject/wiki/Exclude-specific-countries)  
  > - Option to remember last selection.

  * If you are using version lower than 2.0.0 then please read [update guide](https://github.com/hbb20/CountryCodePickerProject/wiki/Update-Guide-for-v2.0.0) before upgrading to v2.0.0.*

Features
--------
If you prefer experience along with explanations, an demo android app is available that demonstrates all the features of this library. Click below button to download from Playstore.
<br/><a href="https://goo.gl/zI2cY2"><img src="http://www.android.com/images/brand/get_it_on_play_logo_large.png"/></a>

* [Super easy to integrate ](https://github.com/hbb20/CountryCodePickerProject/wiki/How-to-integrate-into-your-project)
* [Full Number Support](https://github.com/hbb20/CountryCodePickerProject/wiki/Full-Number-Support)
	- Auto-Formatting
	- Number Validation
	- Validity Change Listener
	- Read / Load full number
* [Use as Country Selector / Country Spinner](https://github.com/hbb20/CountryCodePickerProject/wiki/Use-as-a-Country-Selector)
* [Country preference](https://github.com/hbb20/CountryCodePickerProject/wiki/Country-Preference)
* [Custom master list](https://github.com/hbb20/CountryCodePickerProject/wiki/Custom-Master-Country-List)
* [Country Selection Change Listener](https://github.com/hbb20/CountryCodePickerProject/wiki/Country-Change-Listener)
* [Multi-language support](https://github.com/hbb20/CountryCodePickerProject/wiki/Multi-Language-Support)
* Customizable [CCP theme](https://github.com/hbb20/CountryCodePickerProject/wiki/CCP-Theme-Customization) and [Dialog Theme](https://github.com/hbb20/CountryCodePickerProject/wiki/CCP-Dialog-Theme-Customization) 
* [Auto detect Country](https://github.com/hbb20/CountryCodePickerProject/wiki/Auto-detect-country)
* [Auto detect Language](https://github.com/hbb20/CountryCodePickerProject/wiki/XML-Properties#appccp_autodetectlanguagetrue-default--false-)
* [Remembers last selection](https://github.com/hbb20/CountryCodePickerProject/wiki/XML-Properties#appccp_rememberlastselectiontrue-default--false-)
* [Fast Scroller](https://github.com/hbb20/CountryCodePickerProject/wiki/XML-Properties#appccpdialog_showfastscrollerfalse-default-true-) 


## Available XML properties
To check all xml properties available for CCP and CCP Selection ppDialog, please visit the [wiki page](https://github.com/hbb20/CountryCodePickerProject/wiki/XML-Properties).

Change log
--------
##### Version 2.2.0 (April 20, 2018)
- Improved international phone formatting.
- Removes intermediate solution for national phone hint (ccp_hintExampleNumberFormat is no longer supported).
- Add/Correct some country flags.
- Uses latest [libphonenumber (Optimized for android)](https://github.com/MichaelRocks/libphonenumber-android) library.
- FailureListener interface to listen to onCountryAutoDetectionFailed [Issue#186](https://github.com/hbb20/CountryCodePickerProject/issues/186).

##### Version 2.1.9 (March 21, 2018)
- Adds Swedish language support ([Pull request](https://github.com/hbb20/CountryCodePickerProject/pull/167) by [Tobias Hillén](https://github.com/tobiashillen))
- Adds Kosovo Country  ([Pull request](https://github.com/hbb20/CountryCodePickerProject/pull/166) by [Aleksei Kliuev](https://github.com/aleksei-klv))
- Adds Guadeloupe Countries [Issue#170](https://github.com/hbb20/CountryCodePickerProject/issues/170)
- Understands difference between Isle of Man country and UK numbers. [Issue#168](https://github.com/hbb20/CountryCodePickerProject/issues/168)
- Feature to remove country name code from CCP Dialog [Issue#159](https://github.com/hbb20/CountryCodePickerProject/issues/159)
- Adds ccp_hintExampleNumberFormat to address cases like [Issue#154](https://github.com/hbb20/CountryCodePickerProject/issues/154)

##### version 2.1.4 (Jan 29, 2018)
- Handles national trunk prefixes correctly. [Issue#149](https://github.com/hbb20/CountryCodePickerProject/issues/149)
- Feature to add selected country's example number as hint of carrier number edit text. [Wiki Page](https://github.com/hbb20/CountryCodePickerProject/wiki/Example-phone-number-as-edittext-hint)
- Corrected dimension of French Guiana flag ([Pull request](https://github.com/hbb20/CountryCodePickerProject/pull/148) by [Gautier MECHLING](https://github.com/Nilhcem))
- Feature to exclude specific countries from the list. [Wiki Page](https://github.com/hbb20/CountryCodePickerProject/wiki/Exclude-specific-countries)

##### version 2.1.2 (Jan 6, 2018)
- Adds Punjabi language support [Pull Request](https://github.com/hbb20/CountryCodePickerProject/pull/141) By [Dhruv Bhakta](https://github.com/DBB411)
- Corrected Arabic translation by [Ahmed Wahdan](https://github.com/WahdanZ)
- Country name textView, Flag imageView, Arrow imageView are now publicly accessible through getter-setters.  


##### version 2.1.1 (Dec 13, 2017)
- Opens Country class (Renamed to "CCPCountry" to avoid naming confusion) ([issue#136](https://github.com/hbb20/CountryCodePickerProject/issues/136))
- Fixes preview in Android Studio 3
- Auto detects country while typing based on area code (for countries with code "+1") ([issue#140](https://github.com/hbb20/CountryCodePickerProject/issues/140))
- Cursor color follows ccpDialog_searchEditTextTint color ([issue#131](https://github.com/hbb20/CountryCodePickerProject/issues/131))
- Possible fix for crash ([issue#67](https://github.com/hbb20/CountryCodePickerProject/issues/67))

For earlier versions, check [full log](https://github.com/hbb20/CountryCodePickerProject/wiki/Version-Change-Log).

------

## Credits
- [Fast Scroller library](https://github.com/FutureMind/recycler-fast-scroll) by [Future Minds](https://github.com/FutureMind)
- Optimized [Android port](https://github.com/MichaelRocks/libphonenumber-android) of [libphonenumber](https://github.com/googlei18n/libphonenumber) by [Michael Rozumyanskiy](https://github.com/MichaelRocks) 
- Hebrew translation by [David Brownstone](https://github.com/dfbrownstone)
- Chinese translation by [KENNETH2008](https://github.com/kenneth2008)
- Indonesia translation by [Maulana Firdaus](https://github.com/firdausmaulan)
- Spanish translation by [Armando Gomez](https://github.com/ArmandoGomez)
- Turkish translation by [Ugurcan Yildirim](https://github.com/ugurcany)
- Ukrainian language support by [VyacheslavMartynenko](https://github.com/VyacheslavMartynenko)
- Italian language support by [Fabrizio Gueli](https://github.com/fabriziogueli)
- Korean language support by [kduhyun](https://github.com/kduhyun)
- Portuguese translation corrections by [Elifázio Bernardes da Silva](https://github.com/elifazio)
- Flag border color option by [Maulana Firdaus](https://github.com/firdausmaulan)
- Dutch language support by [Bozintan Iuliana](https://github.com/IulianaDiana)
- Punjabi language support by [Dhruv Bhakta](https://github.com/DBB411)
- Arabic translation corrections by [Ahmed Wahdan](https://github.com/WahdanZ)
- Swedish language support by [Tobias Hillén](https://github.com/tobiashillen)
- Addition of Kosovo Country by [Aleksei Kliuev](https://github.com/aleksei-klv)

# Contribution
- To add a new country, follow the [guide to add new country](https://github.com/hbb20/CountryCodePickerProject/wiki/Guide-to-add-new-country-in-list).
- To add a new Language support, follow the [guide to add new language support](https://github.com/hbb20/CountryCodePickerProject/wiki/Add-New-Language-Support).



## License

[Apache Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

    Copyright (C) 2016 Harsh Bhakta

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
