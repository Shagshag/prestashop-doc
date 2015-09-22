RangeWeightCore
===============






* Class name: RangeWeightCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\range\RangeWeight.php line 27





Properties
----------


### $id_carrier

    public mixed $id_carrier





* Visibility: **public**
* This property is defined in classes\range\RangeWeight.php line 29


### $delimiter1

    public mixed $delimiter1





* Visibility: **public**
* This property is defined in classes\range\RangeWeight.php line 30


### $delimiter2

    public mixed $delimiter2





* Visibility: **public**
* This property is defined in classes\range\RangeWeight.php line 31


### $definition

    public mixed $definition = array('table' => 'range_weight', 'primary' => 'id_range_weight', 'fields' => array('id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'delimiter1' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat', 'required' => true), 'delimiter2' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\range\RangeWeight.php line 36


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectNodeName' => 'weight_range', 'objectsNodeName' => 'weight_ranges', 'fields' => array('id_carrier' => array('xlink_resource' => 'carriers')))





* Visibility: **protected**
* This property is defined in classes\range\RangeWeight.php line 46


Methods
-------


### add

    boolean RangeWeightCore::add(boolean $autodate, boolean $null_values)

Override add to create delivery value for all zones



* Visibility: **public**
* This method is defined in classes\range\RangeWeight.php line 62


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### getRanges

    array RangeWeightCore::getRanges($id_carrier)

Get all available price ranges



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\range\RangeWeight.php line 89


#### Arguments
* $id_carrier **mixed**



### rangeExist

    mixed RangeWeightCore::rangeExist($id_carrier, $delimiter1, $delimiter2)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\range\RangeWeight.php line 98


#### Arguments
* $id_carrier **mixed**
* $delimiter1 **mixed**
* $delimiter2 **mixed**



### isOverlapping

    mixed RangeWeightCore::isOverlapping($id_carrier, $delimiter1, $delimiter2, $id_rang)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\range\RangeWeight.php line 107


#### Arguments
* $id_carrier **mixed**
* $delimiter1 **mixed**
* $delimiter2 **mixed**
* $id_rang **mixed**

