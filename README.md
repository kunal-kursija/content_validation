This module was created to support my DCLondon session on "Decoupling 
Entity-Validations from Entity-Forms".

* Session Details: https://drupalcamp.london/session/decoupling-entity-validations-entity-forms

Developer Info: The file `content_validation.module` defines following:
* (1)`hook_form_BASE_FORM_ID_alter()` This is a old way of adding validations to 
forms. [Comment call to #validate function if you are going to use #2 and #3]
* (2)`content_validation_entity_bundle_field_info_alter()` for adding validation 
constraints to Entity Fields. 
* (3)`hook_entity_type_alter()` for adding validation constraints to Entities.
