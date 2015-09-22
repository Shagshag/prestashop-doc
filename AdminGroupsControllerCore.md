AdminGroupsControllerCore
===============






* Class name: AdminGroupsControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminGroupsController.php line 30





Properties
----------


### $object

    public \Group $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminGroupsController.php line 30


Methods
-------


### __construct

    mixed AdminGroupsControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminGroupsController.php line 32




### setMedia

    mixed AdminGroupsControllerCore::setMedia()





* Visibility: **public**
* This method is defined in controllers\admin\AdminGroupsController.php line 141




### initToolbar

    mixed AdminGroupsControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminGroupsController.php line 148




### initPageHeaderToolbar

    mixed AdminGroupsControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminGroupsController.php line 161




### initProcess

    mixed AdminGroupsControllerCore::initProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminGroupsController.php line 174




### renderView

    mixed AdminGroupsControllerCore::renderView()





* Visibility: **public**
* This method is defined in controllers\admin\AdminGroupsController.php line 195




### renderCustomersList

    mixed AdminGroupsControllerCore::renderCustomersList($group)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminGroupsController.php line 212


#### Arguments
* $group **mixed**



### renderForm

    mixed AdminGroupsControllerCore::renderForm()





* Visibility: **public**
* This method is defined in controllers\admin\AdminGroupsController.php line 251




### formatCategoryDiscountList

    mixed AdminGroupsControllerCore::formatCategoryDiscountList($id_group)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminGroupsController.php line 360


#### Arguments
* $id_group **mixed**



### formatModuleListAuth

    mixed AdminGroupsControllerCore::formatModuleListAuth($id_group)





* Visibility: **public**
* This method is defined in controllers\admin\AdminGroupsController.php line 393


#### Arguments
* $id_group **mixed**



### processSave

    mixed AdminGroupsControllerCore::processSave()





* Visibility: **public**
* This method is defined in controllers\admin\AdminGroupsController.php line 444




### validateDiscount

    mixed AdminGroupsControllerCore::validateDiscount($reduction)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminGroupsController.php line 456


#### Arguments
* $reduction **mixed**



### ajaxProcessAddCategoryReduction

    mixed AdminGroupsControllerCore::ajaxProcessAddCategoryReduction()





* Visibility: **public**
* This method is defined in controllers\admin\AdminGroupsController.php line 465




### updateRestrictions

    mixed AdminGroupsControllerCore::updateRestrictions()

Update (or create) restrictions for modules by group



* Visibility: **protected**
* This method is defined in controllers\admin\AdminGroupsController.php line 489




### updateCategoryReduction

    mixed AdminGroupsControllerCore::updateCategoryReduction()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminGroupsController.php line 504




### processChangeShowPricesVal

    mixed AdminGroupsControllerCore::processChangeShowPricesVal()

Toggle show prices flag



* Visibility: **public**
* This method is defined in controllers\admin\AdminGroupsController.php line 540




### printShowPricesIcon

    string AdminGroupsControllerCore::printShowPricesIcon($id_group, $tr)

Print enable / disable icon for show prices option



* Visibility: **public**
* This method is defined in controllers\admin\AdminGroupsController.php line 561


#### Arguments
* $id_group **mixed** - &lt;p&gt;integer Group ID&lt;/p&gt;
* $tr **mixed** - &lt;p&gt;array Row data&lt;/p&gt;



### renderList

    mixed AdminGroupsControllerCore::renderList()





* Visibility: **public**
* This method is defined in controllers\admin\AdminGroupsController.php line 572




### displayEditLink

    mixed AdminGroupsControllerCore::displayEditLink($token, $id, $name)





* Visibility: **public**
* This method is defined in controllers\admin\AdminGroupsController.php line 598


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**

