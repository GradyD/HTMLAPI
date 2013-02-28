<php>

/*
  Plugin Name: App Data API
	Plugin URI: notyetpublished
	Description: Displays Android App Data using the App Brain API
	Author: Grady
	Version: 0.1-alpha
	Author URI: Notyetpublished
	License: GPL
 */


class App_Data_API {

  function __construct() {
    add_shortcode('app_data',array($this,'app_data_shortcode'));
  }

  function app_data_shortcode() { ?>
    <div class="api">
      <div style="margin: 0 auto; max-width: 700px;">
    <div style="float: left;">
      <table style="background-color: #e7e7e27; border-color: #e2e2e2;">
        <td style="vertical-align: middle; text-align: center; background: #e2e2e2; border-top: 0px; ">
          <a rel="nofollow" href="https://play.google.com/store/apps/<!---package name--->" class="no_ul external" target="_blank">
        <img src="http://developer.android.com/images/brand/Google_Play_Store_96.png" style="width:90px; border:0" alt="<!---Verbage--->" title="<!---Verbage--->">
          </a>
        </td>
      </table>
    </div>
    <div style="float: left;">
      <div class='appbrain-app'>
        <a href='http://www.appbrain.com/app/<!---package name--->' style='font-size: 11px; color: #555; font-family: Arial, sans-serif;'></a>
      </div> 
      <script type='text/javascript' language='javascript' src='http://www.appbrain.com/api/api.nocache.js'></script>
    </div>
      </div>
    </div><?php
  } 
}
new App_Data_API();

</php>
