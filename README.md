sample application for students #3

#CategoryController

&#91;OperationContract&#93;
IEnumerable<Category> SelectAll();

[create an anchor](#anchors-in-markdown)


* [SelectAll](#selectall)
* SelectById
* SelectByName
* Create
* Check

 
# Controllers description
# ICategoryController.SelectAll

# anchors-in-markdown
## SelectAll

|Method name| Arguments|Return|Description
| :-- | :-- | :-- | :-- |
| SelectAll  | ```void``` | ```IEnumerable<Category>```| Gets full category list. |
| SelectById  | ```int id```  | ```Category```  | Fetches single category by primary key. |
| SelectByName  | ```IEnumerable<Category>```  | ```string name```  | Fetches category list with target name. |
| Create  | ```Category```  | ```string name```  | Category a new instance of the category. |


