Fixed version of the Magento Database Repair Tool

Based on ver 1.2 - Added September 19, 2014 https://www.magentocommerce.com/download

The Database Repair Tool compares 2 databases (reference and target), and updates the target database so it has the same structure as the reference database


 - Fixed issue with "Deprecated: mysql_escape_string(): This function is deprecated; use mysql_real_escape_string() instead."

 You can use the fixed file or apply "deprecated-mysql_escape_string-patch.diff" patch to your copy by yourself