<h1>Base Seo Changes</h1>

<h2>Installation:</h2>
<strong>Composer:</strong> <br/>

composer require andyworkbase/base-seo-changes --no-update<br/>
composer update andyworkbase/base-seo-changes<br/>

<strong>Manually:</strong> <br/>
1) unpack extension package and upload them into Magento root directory/app/code/
2) php bin/magento setup:upgrade
3) php bin/magento setup:di:compile
4) php bin/magento setup:static-content:deploy

<strong>Configuration</strong> - Stores -> Configuration -> MageCloud -> Base Seo Changes

<h2>Features:</h2>
<ul>
<li>support multistore;</li>
<li>add canonical URL;</li>
<li>set correct meta robots strategy.</li>
</ul>
