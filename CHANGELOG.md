## 0.8.0

Features:
 - New endpoints:
   - delete_beta_tester
   - read_beta_tester_information
   - modify_beta_group
   - delete_beta_group
   - read_beta_group_information
   - read_beta_app_localization_information
   - create_beta_app_localization
   - modify_registered_device
   - read_beta_app_review_submission_information
 - Collect anonymous usage statistics

Breaking changes API:
 - new parameters for create_beta_tester
 - new parameters for create_beta_group
 - new parameters for submit_app_for_beta_review
 - register_device renamed to register_new_device 

## 0.7.0

Features:
 - New endpoint: register_device (@BalestraPatrick)

## 0.6.0

Features:
 - New endpoints: invite_user and read_user_invitation_information (@BalestraPatrick)

Bugfixes:
 - Fixes create_beta_tester endpoint URL (@BalestraPatrick)

## 0.5.1

Bugfixes:
 - Fixes token re-generation (@gsaraceno)

## 0.5.0

Features:
 -  Handle listing all resources in the provisioning section (devices thanks to @EricG-Personal)

## 0.4.1

Features:
 - Allow to query resources sorted
 - Allow passing key as a string value (@kpotehin)

Bugfixes:
 - Fixed sort param in reports (@kpotehin)

## 0.4.0

Features:
 - Handle fetching related resources (@WangYi)

Bugfixes:
 - When paging resources, fix missing resource in the first page (@WangYi)

## 0.3.0

Features:
  - Complete API rewrite, "list" methods return an iterator over resources, "get" method returns a resource 
  - Handles all GET endpoints (except the new "Provisioning" section)
  - Handle pagination
  - Handle downloading Finance and Sales reports

## 0.2.1

Bugfixes:

  - Cryptography dependency is required

## 0.2.0

Features:

  - Added more functions (@fehmitoumi)

## 0.1.0

Features:

  - Initial Release
