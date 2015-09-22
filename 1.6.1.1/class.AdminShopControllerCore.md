Class AdminShopControllerCore
=====================





* Class name: AdminShopControllerCore
* Parent class: [AdminController](class.AdminControllerCore)
* Source: [controllers/admin/AdminShopController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L30)



Properties
----------

* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [afterAdd](#method-afterAdd)
* [afterUpdate](#method-afterUpdate)
* [ajaxProcessTree](#method-ajaxProcessTree)
* [displayAjaxGetCategoriesFromRootCategory](#method-displayAjaxGetCategoriesFromRootCategory)
* [displayEditLink](#method-displayEditLink)
* [getList](#method-getList)
* [initCategoriesAssociation](#method-initCategoriesAssociation)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initToolbar](#method-initToolbar)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processDelete](#method-processDelete)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [viewAccess](#method-viewAccess)




Properties
----------


### <a name="property-$object"></a>$object

    public \Shop $object





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminShopControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L32)




### <a name="method-afterAdd"></a>afterAdd

    boolean AdminShopControllerCore::afterAdd(\Shop $new_shop)





* Visibility: **protected**
* Source: [controllers/admin/AdminShopController.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L298)


#### Arguments
* $new_shop **[Shop](class.ShopCore)**



### <a name="method-afterUpdate"></a>afterUpdate

    boolean AdminShopControllerCore::afterUpdate(\Shop $new_shop)





* Visibility: **protected**
* Source: [controllers/admin/AdminShopController.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L323)


#### Arguments
* $new_shop **[Shop](class.ShopCore)**



### <a name="method-ajaxProcessTree"></a>ajaxProcessTree

    mixed AdminShopControllerCore::ajaxProcessTree()





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 757](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L757)




### <a name="method-displayAjaxGetCategoriesFromRootCategory"></a>displayAjaxGetCategoriesFromRootCategory

    mixed AdminShopControllerCore::displayAjaxGetCategoriesFromRootCategory()





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L222)




### <a name="method-displayEditLink"></a>displayEditLink

    mixed AdminShopControllerCore::displayEditLink($token, $id, $name)





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 707](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L707)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-getList"></a>getList

    mixed AdminShopControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L348)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-initCategoriesAssociation"></a>initCategoriesAssociation

    mixed AdminShopControllerCore::initCategoriesAssociation($id_root)





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 727](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L727)


#### Arguments
* $id_root **mixed**



### <a name="method-initContent"></a>initContent

    mixed AdminShopControllerCore::initContent()





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L140)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminShopControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L92)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminShopControllerCore::initToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L119)




### <a name="method-postProcess"></a>postProcess

    mixed AdminShopControllerCore::postProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L238)




### <a name="method-processAdd"></a>processAdd

    mixed AdminShopControllerCore::processAdd()

Object creation



* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 647](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L647)




### <a name="method-processDelete"></a>processDelete

    mixed AdminShopControllerCore::processDelete()





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L279)




### <a name="method-renderForm"></a>renderForm

    mixed AdminShopControllerCore::renderForm()





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L366)




### <a name="method-renderList"></a>renderList

    mixed AdminShopControllerCore::renderList()





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L199)




### <a name="method-viewAccess"></a>viewAccess

    mixed AdminShopControllerCore::viewAccess($disable)





* Visibility: **public**
* Source: [controllers/admin/AdminShopController.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminShopController.php#L87)


#### Arguments
* $disable **mixed**

