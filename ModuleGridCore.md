ModuleGridCore
===============






* Class name: ModuleGridCore
* Namespace: 
* This is an **abstract** class
* Parent class: [Module](ModuleCore)
* This class is defined in classes\module\ModuleGrid.php line 27





Properties
----------


### $_employee

    protected mixed $_employee





* Visibility: **protected**
* This property is defined in classes\module\ModuleGrid.php line 29


### $_values

    protected array $_values = array()





* Visibility: **protected**
* This property is defined in classes\module\ModuleGrid.php line 32


### $_totalCount

    protected integer $_totalCount





* Visibility: **protected**
* This property is defined in classes\module\ModuleGrid.php line 35


### $_title

    protected mixed $_title





* Visibility: **protected**
* This property is defined in classes\module\ModuleGrid.php line 38


### $_start

    protected mixed $_start





* Visibility: **protected**
* This property is defined in classes\module\ModuleGrid.php line 41


### $_limit

    protected mixed $_limit





* Visibility: **protected**
* This property is defined in classes\module\ModuleGrid.php line 44


### $_sort

    protected mixed $_sort = null





* Visibility: **protected**
* This property is defined in classes\module\ModuleGrid.php line 47


### $_direction

    protected mixed $_direction = null





* Visibility: **protected**
* This property is defined in classes\module\ModuleGrid.php line 50


### $_render

    protected \ModuleGridEngine $_render





* Visibility: **protected**
* This property is defined in classes\module\ModuleGrid.php line 53


Methods
-------


### getData

    mixed ModuleGridCore::getData()





* Visibility: **protected**
* This method is **abstract**.
* This method is defined in classes\module\ModuleGrid.php line 55




### setEmployee

    mixed ModuleGridCore::setEmployee($id_employee)





* Visibility: **public**
* This method is defined in classes\module\ModuleGrid.php line 57


#### Arguments
* $id_employee **mixed**



### setLang

    mixed ModuleGridCore::setLang($id_lang)





* Visibility: **public**
* This method is defined in classes\module\ModuleGrid.php line 62


#### Arguments
* $id_lang **mixed**



### create

    mixed ModuleGridCore::create($render, $type, $width, $height, $start, $limit, $sort, $dir)





* Visibility: **public**
* This method is defined in classes\module\ModuleGrid.php line 67


#### Arguments
* $render **mixed**
* $type **mixed**
* $width **mixed**
* $height **mixed**
* $start **mixed**
* $limit **mixed**
* $sort **mixed**
* $dir **mixed**



### render

    mixed ModuleGridCore::render()





* Visibility: **public**
* This method is defined in classes\module\ModuleGrid.php line 92




### engine

    mixed ModuleGridCore::engine($params)





* Visibility: **public**
* This method is defined in classes\module\ModuleGrid.php line 97


#### Arguments
* $params **mixed**



### csvExport

    mixed ModuleGridCore::csvExport($datas)





* Visibility: **protected**
* This method is defined in classes\module\ModuleGrid.php line 153


#### Arguments
* $datas **mixed**



### _displayCsv

    mixed ModuleGridCore::_displayCsv()





* Visibility: **protected**
* This method is defined in classes\module\ModuleGrid.php line 181




### getDate

    mixed ModuleGridCore::getDate()





* Visibility: **public**
* This method is defined in classes\module\ModuleGrid.php line 192




### getLang

    mixed ModuleGridCore::getLang()





* Visibility: **public**
* This method is defined in classes\module\ModuleGrid.php line 197


