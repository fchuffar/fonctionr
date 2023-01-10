# fonctionr

An empty R package build as a prototype. It illustrates development practices in R: documentation, literate programming, testing, versioning, continuous integration.

**Developement**
  
**Install**
  
```
devtools::install_github("fchuffar/fonctionr")
```
  
  
**Developement**

```
devtools::document(); 
devtools::install(); 
Sys.setenv('_R_CHECK_SYSTEM_CLOCK_' = 0)
devtools::check()
devtools::build()
```