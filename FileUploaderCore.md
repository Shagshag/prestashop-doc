FileUploaderCore
===============






* Class name: FileUploaderCore
* Namespace: 
* This class is defined in classes\FileUploader.php line 27





Properties
----------


### $allowedExtensions

    protected mixed $allowedExtensions = array()





* Visibility: **protected**
* This property is defined in classes\FileUploader.php line 29


### $file

    protected \QqUploadedFileXhr $file





* Visibility: **protected**
* This property is defined in classes\FileUploader.php line 32


### $sizeLimit

    protected mixed $sizeLimit





* Visibility: **protected**
* This property is defined in classes\FileUploader.php line 33


Methods
-------


### __construct

    mixed FileUploaderCore::__construct(array $allowedExtensions, $sizeLimit)





* Visibility: **public**
* This method is defined in classes\FileUploader.php line 35


#### Arguments
* $allowedExtensions **array**
* $sizeLimit **mixed**



### toBytes

    mixed FileUploaderCore::toBytes($str)





* Visibility: **protected**
* This method is defined in classes\FileUploader.php line 51


#### Arguments
* $str **mixed**



### handleUpload

    mixed FileUploaderCore::handleUpload()

Returns array('success'=>true) or array('error'=>'error message')



* Visibility: **public**
* This method is defined in classes\FileUploader.php line 66


