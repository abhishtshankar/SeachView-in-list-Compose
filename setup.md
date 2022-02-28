# Setup Guide
## Table of Contents

* [Getting Started](#getting-started)
    * [Prerequisites](#prerequisites)
* [SSH Key](#ssh-key)
* [Resolving Errors](#resolving-errors)

## Getting Started

Use SSH method for this, HTTPS method can't be used as it asks for authentication.

### Prerequisites
- Android Studio Bumblee
- Homebrew
- Java 11
- JDK JRE 11
  
## SSH key.
Connecting with SSH key:
- Generate new SSH key
- Add a new SSH keep
  
  For help on SSH keys :
  https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh


### Now set the path in android studio :

Go to Android Studio Menu > 
Preferneces > 
Search for Gradle under the search option >
From the Gradle JDK dropdown menu, Select Java 11 version.

<img width="1440" alt="Screenshot 2022-02-28 at 5 08 27 PM" src="https://user-images.githubusercontent.com/99014438/155977405-69603a44-caed-4ef6-8c07-621bd6bfbf75.png">

<img width="1440" alt="Screenshot 2022-02-28 at 5 08 58 PM" src="https://user-images.githubusercontent.com/99014438/155977382-df648a74-82c1-4e3d-8e06-0952bef0fb76.png">

### Now **invalidate cache and restart** in Android studio.

## Resolving Errors
 If you get any Gradle error, **Add to local.properties**

```
MAPS_API_KEY=AIzaSyBNwM26wEqperIGrZIOQNDBxiNXvPcmCtc


api_ci="https://sejayauat.finflux.io/"

client_ci_secret="mobile123"

client_ci_id="mobile-app"

api_ci_provider="fineract-provider/api/"

platform_tenantId_ci="sejayauat"

secret_login_password_key="passwordfinfluxsecure"

STORE_FILE =loanbook-release.jks

STORE_PASSWORD=finflux@123

KEY_PASSWORD=conflux@123

KEY_ALIAS=upload
```
<img width="1440" alt="Screenshot 2022-02-28 at 12 32 20 AM" src="https://user-images.githubusercontent.com/99014438/156041595-413e1fd6-bc7f-4d30-a63e-11dcac25513b.png">







