Yild / Finto autotranslate

This module offers the option to automatically translate yild_tags term
titles after terms are fetched from Finto API. This requires term title
to be set as a translateable field.

There are a few new variables that can be changed on Yild-setting page at:
 admin/config/yild/general

Please note:
 This functionality requires a specific Drupal setup where yild_tags
 themselves are language neutral (entity_translation) and their title
 field has been replaced with field provided by title-module.
 This title-field needs to be set translateable, and its name should be:
 "name_field".
