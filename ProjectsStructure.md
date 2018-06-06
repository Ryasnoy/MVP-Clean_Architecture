# Project's Structure #

#### 1. *AppDelegate.swift* ####
#### 2. The `Model` folder includes all common models ####
#### 3. The `Basic` folder includes all parent's classes ####
#### 4. The `Helpers` folder includes files and folders ####
   * *Constants.swift*
   * The `Tools` folder
   * The `Extensions` folder includes common extensions. (Example: *UIViewController.swift*)
#### 5. The `Modules` folder includes all modules ####

Structure of the module:

* The `Model` folder includes models relating to the module
* The `Views` folder: 
  * *Module.storyboard*
  * The `Cell` folder:
    * *Cell.xib*
    * *Cell.swift*
* The `Module` folder includes files of the module
  * *ModuleViewController.swift*
  * *ModulePresenter.swift*                                
  * *ModuleRouter.swift*
  * *ModuleConfigurator.swift*
  * The `Interactors` folder includes interactors files

#### 6. The `Network` folder includes all the work with network ####
#### 7. The `Resources` folder includes all the resources files and plists ####
#### 8. The `DataBase` folder includes all the files for working with DataBase ####


