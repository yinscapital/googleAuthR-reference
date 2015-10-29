# News Updates

# v1.1.9002

* Add `simplifyVector = FALSE` to content parsing for compatibility for some APIs
* Batch Google API requests now implemented.  See readme or `?gar_batch` and `?gar_batch_walk` for details.
* If data parsing fails, return the raw content so you can test and modify your data parsing function 

# v1.1.9001

* Missed Jenny credit now corrected
* Add tip about using `!is.null(access_token())` to detect login state
* Add HTTP backoff for certain errors (#6) from Johann
* Remove possible NULL entries from path and pars argument lists
* Reduced some unnecessary message feedback
* moved `with_shiny` environment lookup to within generated function
* added gzip to headers

# v1.1 - CRAN

* Shiny compatibility
* Local authentication compatibility