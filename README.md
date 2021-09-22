# mercurial
With Mercurial you can use a multitude of different workflows. This page shows some of them, including their use cases. It is intended to make it easy for beginners of version tracking to get going instantly and learn completely incrementally. It doesn't explain the concepts used, because there are already many other great resources doing that.  Alternatives to this guide and further reading:  Tutorial - a more exhaustive tutorial. Mercurial: The Definitive Guide - a very detailed description of Mercurial including behind the scenes, an indepth article on the design of Mercurial. Understanding Mercurial - the concepts behind Mercurial. Note:  This guide doesn't require any prior knowledge of version control systems (though subversion users will likely feel at home quite quickly). Basic command line abilities are helpful, because we'll use the command line client. Basic workflows We go from simple to more complex workflows. Those further down build on previous workflows.  Log keeping  Use Case The first workflow is also the easiest one: You want to use Mercurial to be able to look back when you did which changes.  This workflow only requires an installed Mercurial and write access to some file storage (you almost definitely have that :) ). It shows the basic techniques for more complex workflows.  prepare Mercurial As a first step, you should teach your Mercurial name. So you open the file ~ / .hgrc (or Mercurial.ini in your home directory for Windows) with a text editor and add the ui section (user interaction) with your user name: if You are systems that project members checked or validated changes in the source code, or by using command-line tools to upload files to the project of the "Downloads" tab. Password is: kt2qK3qV5PX4  http://git-scm.com/downloads  http://mercurial.selenic.com/downloads
{
  "project_info": {
    "project_number": "221841464021",
    "firebase_url": "https://helpful-monitor-120514.firebaseio.com",
    "project_id": "helpful-monitor-120514",
    "storage_bucket": "helpful-monitor-120514.appspot.com"
  },
  "client": [
    {
      "client_info": {
        "mobilesdk_app_id": "1:221841464021:android:c44a1a026face3cb",
        "android_client_info": {
          "package_name": "br.com.omegacodeapps.Mercurius"
        }
      },
      "oauth_client": [
        {
          "client_id": "221841464021-nphfkgebd77acin649d66htds3badl8t.apps.googleusercontent.com",
          "client_type": 3
        }
      ],
      "api_key": [
        {
          "current_key": "AIzaSyDDzwJ9uff--ENue0ic1Xh2Ah_TZDnhSiU"
        }
      ],
      "services": {
        "appinvite_service": {
          "other_platform_oauth_client": [
            {
              "client_id": "221841464021-1aig4qr52kjru8tar7m7n758mgjmd0r4.apps.googleusercontent.com",
              "client_type": 3
            },
            {
              "client_id": "221841464021-0fclfvejaha788688lqk38999jf5ves9.apps.googleusercontent.com",
              "client_type": 2,
              "ios_info": {
                "bundle_id": "br.com.omegacodeapps.Mercurius",
                "app_store_id": "app-1-1078089407974-ios-c44a1a026face3cb"
              }
            }
          ]
        }
      },
      "admob_app_id": "ca-app-pub-4348171683695472~6739517734"
    },
    {
      "client_info": {
        "mobilesdk_app_id": "1:221841464021:android:fc4ecca64b4b0e9c4b205c",
        "android_client_info": {
          "package_name": "com.lyoomatch.jewelscrush.princessadventure"
        }
      },
      "oauth_client": [
        {
          "client_id": "221841464021-nphfkgebd77acin649d66htds3badl8t.apps.googleusercontent.com",
          "client_type": 3
        }
      ],
      "api_key": [
        {
          "current_key": "AIzaSyDDzwJ9uff--ENue0ic1Xh2Ah_TZDnhSiU"
        }
      ],
      "services": {
        "appinvite_service": {
          "other_platform_oauth_client": [
            {
              "client_id": "221841464021-1aig4qr52kjru8tar7m7n758mgjmd0r4.apps.googleusercontent.com",
              "client_type": 3
            },
            {
              "client_id": "221841464021-0fclfvejaha788688lqk38999jf5ves9.apps.googleusercontent.com",
              "client_type": 2,
              "ios_info": {
                "bundle_id": "br.com.omegacodeapps.Mercurius",
                "app_store_id": "app-1-1078089407974-ios-c44a1a026face3cb"
              }
            }
          ]
        }
      },
      "admob_app_id": "ca-app-pub-4348171683695472~8408266779"
    },
    {
      "client_info": {
        "mobilesdk_app_id": "1:221841464021:android:d294275eb560c627",
        "android_client_info": {
          "package_name": "com.mercurial.app"
        }
      },
      "oauth_client": [
        {
          "client_id": "221841464021-nphfkgebd77acin649d66htds3badl8t.apps.googleusercontent.com",
          "client_type": 3
        }
      ],
      "api_key": [
        {
          "current_key": "AIzaSyDDzwJ9uff--ENue0ic1Xh2Ah_TZDnhSiU"
        }
      ],
      "services": {
        "appinvite_service": {
          "other_platform_oauth_client": [
            {
              "client_id": "221841464021-1aig4qr52kjru8tar7m7n758mgjmd0r4.apps.googleusercontent.com",
              "client_type": 3
            },
            {
              "client_id": "221841464021-0fclfvejaha788688lqk38999jf5ves9.apps.googleusercontent.com",
              "client_type": 2,
              "ios_info": {
                "bundle_id": "br.com.omegacodeapps.Mercurius",
                "app_store_id": "app-1-1078089407974-ios-c44a1a026face3cb"
              }
            }
          ]
        }
      },
      "admob_app_id": "ca-app-pub-4348171683695472~3786051331"
    }
  ],
  "configuration_version": "1"
}
