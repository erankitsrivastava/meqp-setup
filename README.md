# meqp-setup

Run the below commands :
cd move_to_the_correct_directory_with_correct_permission

wget https://raw.githubusercontent.com/erankitsrivastava/meqp-setup/master/meqp-setup-xampp.sh

sudo chmod +x meqp-setup-xampp.sh 

sudo ./meqp-setup-xampp.sh 



# How to Use


To generate the report:

phpcs --report=xml --report-file=pat/where/have/to/generate/report/report-8.xml /path/of/the/modules/ --standard=MEQP2 --severity=8 -p


# Some Extras

===================================================================================================
Updated version

/opt/xampp/7.0/htdocs/keep/meqp/updated/magento-coding-standard/vendor/bin/phpcs --standard=Magento2 /opt/xampp/7.0/htdocs/keep/meqp/modules/ --report-file=/opt/xampp/7.0/htdocs/keep/meqp/modules/Magento-MEQP-Severity-8.xml

/opt/xampp/7.0/htdocs/keep/meqp/updated/magento-coding-standard/vendor/bin/phpcs  --report=xml --severity=8 --standard=Magento2 /opt/git/CsMarketplace/Marketplace-Basic-Submission/ --report-file=/opt/git/CsMarketplace/Magento-MEQP-Severity-8.xml

===================================================================================================

Examples:
phpcs --report=xml --report-file=/opt/xampp/7.0/htdocs/keep/meqp/modules/Module-MEQP-Severity-8.xml /opt/xampp/7.0/htdocs/keep/meqp/modules/ --standard=MEQP2 --severity=8 -p

phpcs --report=xml --report-file=/opt/xampp/7.0/htdocs/keep/meqp/modules/Magento-MEQP-Severity-8.xml /opt/xampp/7.0/htdocs/keep/meqp/modules/ --standard=Magento2 --severity=8 -p


/opt/lampp/bin/php /usr/local/bin/phpcpd /opt/xampp/7.0/htdocs/keep/meqp/module/ --log-pmd /opt/xampp/7.0/htdocs/keep/meqp/module/cpd_result.xml


phpcs --report=xml --report-file=/opt/xampp/7.0/htdocs/keep/meqp/modules/Magento-MEQP-Severity-8.xml /opt/xampp/7.0/htdocs/keep/meqp/modules/ --standard=Magento2 --severity=8 -p
