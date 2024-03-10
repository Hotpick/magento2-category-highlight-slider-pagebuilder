# magento2-category-list-widget

#Features
TODO: add features list

<h2>Composer Installation Instructions</h2>
Add GIT Repository to composer
<pre>
composer config repositories.hotpick-category-highlight-slider vcs https://github.com/Hotpick/magento2-category-highlight-slider-pagebuilder/
</pre>

After that, need to install this module as follows:
<pre>
  composer require magento/magento-composer-installer
  composer require hotpick/category-highlight-slider
</pre>


<br/>
<h2> Mannual Installation Instructions</h2>
go to Magento2Project root dir 
create following Directory Structure :<br/>
<strong>/Magento2Project/app/code/Hotpick/CategoryHighlightSlider</strong>
you can also create by following command:
<pre>
cd /Magento2Project
mkdir app/code/Hotpick
mkdir app/code/Hotpick/CategoryHighlightSlider
</pre>



<h3> Enable Emizentech/CategoryWidget Module</h3>
to Enable this module you need to follow these steps:

<ul>
<li>
<strong>Enable the Module</strong>
<pre>bin/magento module:enable Hotpick_CategoryHighlightSlider</pre></li>
<li>
<strong>Run Upgrade Setup</strong>
<pre>bin/magento setup:upgrade</pre></li>
<li>
<strong>Re-Compile (in-case you have compilation enabled)</strong>
	<pre>bin/magento setup:di:compile</pre>
</li>
</ul>
