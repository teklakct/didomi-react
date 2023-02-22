
> This is a fork of [@didomi/react](https://github.com/didomi/react) which:
>  - removes vulnerable "dset" [Remove unused dset #55](https://github.com/didomi/react/pull/55)
>  - adds missing dependency ["add prop-types as a dependency"](https://github.com/didomi/react/pull/59)  
>  - updates "nwb" which solve a lot of vulnerabilities reported by npm audit

# Didomi React

[![Didomi](data:image/png;base64,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)](https://didomi.io)

Didomi React is a React component which creates a layer on top of our SDK.

## Install the component

1. Install the library using npm.

```sh
$ npm install --save @teklakct/didomi-react
```
2. Import the module in your app.

```js
import { DidomiSDK } from '@didomi/react';
```

We recommend instantiating the `DidomiSDK` component as early as possible in your React application.
The sooner you instantiate the component, the faster the banner will be displayed or the faster the consents will be shared with your partners and the ads displayed.

## Create the DidomiSDK component

### Instantiate the component with the configuration coming from the Didomi Console (recommended)

1. Create and configure your consent notice in the Console : https://console.didomi.io

2. Instantiate the component in your app
```jsx
<DidomiSDK
  apiKey="API_KEY"
  iabVersion={2} // If you want to support the TCF v1∏, don't forget to change this value, even if you selected the TCF v2 in the console. This parameter will load the correct stub in the React Component
  noticeId="NOTICE_ID" // If you want to target the notice by ID and not by domain
  gdprAppliesGlobally={true}
  sdkPath="https://sdk.privacy-center.org/"
  embedTCFStub={true}
  onReady={didomi => console.log('Didomi SDK is loaded and ready', didomi)}
  onConsentChanged={cwtToken => console.log('A consent has been given/withdrawn', cwtToken)}
  onNoticeShown={() => console.log('Didomi Notice Shown')}
  onNoticeHidden={() => console.log('Didomi Notice Hidden')}
  onNoticeBackdropclick={() => console.log('Didomi Notice Backdrop Click')}
  onNoticeClickAgree={() => console.log('Didomi Notice Click Agree')}
  onNoticeClickMoreInfo={() => console.log('Didomi Notice Click More Info')}
  onPreferencesClickAgreeToAll={() => console.log('Didomi Preferences Click Agree to All')}
  onPreferencesClickDisagreeToAll={() => console.log('Didomi Preferences Click Disagree to All')}
  onPreferencesClickPurposeAgree={purposeId => console.log('Didomi Preferences Click Purpose Agree', purposeId)}
  onPreferencesClickPurposeDisagree={purposeId => console.log('Didomi Preferences Click Purpose Disagree', purposeId)}
  onPreferencesClickViewVendors={() => console.log('Didomi Preferences Click View Vendors')}
  onPreferencesClickSaveChoices={() => console.log('Didomi Preferences Click Save Choices')}
  onPreferencesClickVendorAgree={vendorId => console.log('Didomi Preferences Click Vendor Agree', vendorId)}
  onPreferencesClickVendorDisagree={vendorId => console.log('Didomi Preferences Click Vendor Disagree', vendorId)}
  onPreferencesClickVendorSaveChoices={() => console.log('Didomi Preferences Click Vendor Save Choices')}
/>
```

The Didomi SDK will automatically download its configuration from the Didomi Console.  
Configuration modifications applied through the Didomi Console will be distributed to your users automatically, without modifications to your code.

### Instantiate the component with a local configuration

If you prefer, you can pass a local configuration the Didomi SDK instead of managing the configuration through the Didomi Console.  
With this setup, modifying your configuration will require that you also re-deploy your app.

You can use local configuration to override some remote configuration as well. For instance, you can provide your own notice (see the `Customize the notice` section below) while still using the Didomi Console for the rest of the configuration.

Instantiate the component in your app:
```jsx
const didomiConfig = {  
  app: {
    vendors: {
      iab: {
        all: true
      }
    }
  }
}

...

<DidomiSDK
  config={didomiConfig}
  iabVersion={2} // If you want to support the TCF v1, don't forget to change this value. This parameter will load the correct stub in the React Component
  noticeId="NOTICE_ID" // If you want to target the notice by ID and not by domain
  gdprAppliesGlobally={true}
  sdkPath="https://sdk.privacy-center.org/"
  embedTCFStub={true}
  onReady={didomi => console.log('Didomi SDK is loaded and ready', didomi)}
  onConsentChanged={cwtToken => console.log('A consent has been given/withdrawn', cwtToken)}
  onNoticeShown={() => console.log('Didomi Notice Shown')}
  onNoticeHidden={() => console.log('Didomi Notice Hidden')}
  onNoticeBackdropclick={() => console.log('Didomi Notice Backdrop Click')}
  onNoticeClickAgree={() => console.log('Didomi Notice Click Agree')}
  onNoticeClickMoreInfo={() => console.log('Didomi Notice Click More Info')}
  onPreferencesClickAgreeToAll={() => console.log('Didomi Preferences Click Agree to All')}
  onPreferencesClickDisagreeToAll={() => console.log('Didomi Preferences Click Disagree to All')}
  onPreferencesClickPurposeAgree={purposeId => console.log('Didomi Preferences Click Purpose Agree', purposeId)}
  onPreferencesClickPurposeDisagree={purposeId => console.log('Didomi Preferences Click Purpose Disagree', purposeId)}
  onPreferencesClickViewVendors={() => console.log('Didomi Preferences Click View Vendors')}
  onPreferencesClickSaveChoices={() => console.log('Didomi Preferences Click Save Choices')}
  onPreferencesClickVendorAgree={vendorId => console.log('Didomi Preferences Click Vendor Agree', vendorId)}
  onPreferencesClickVendorDisagree={vendorId => console.log('Didomi Preferences Click Vendor Disagree', vendorId)}
  onPreferencesClickVendorSaveChoices={() => console.log('Didomi Preferences Click Vendor Save Choices')}
/>
  ```

## Configuration options (props)

The following configuration options can be passed as props to the `DidomiSDK` component:

<table>
  <thead>
    <tr>
      <th style="width: 100px;">Name</th>
      <th style="width: 50px;">Type</th>
      <th>Default</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>apiKey</td>
      <td>string</td>
      <td>null</td>
      <td>Your API Key</td>
    </tr>
    <tr>
      <td>iabVersion</td>
      <td>number</td>
      <td>1</td>
      <td>The IAB TCF Version you want to support (1 or 2)</td>
    </tr>
    <tr>
      <td>noticeId</td>
      <td>string</td>
      <td></td>
      <td>The ID of the remote notice you want to target (If you choose not the target by domain)</td>
    </tr>
    <tr>
      <td>config</td>
      <td>object</td>
      <td>{}</td>
      <td>Configuration of the SDK, please go below to see the configuration object structure</td>
    </tr>
    <tr>
      <td>gdprAppliesGlobally</td>
      <td>boolean</td>
      <td>true</td>
      <td>The banner should display to all users no matter where they are located. If you are a non EU-based company then you are only required to collect consent and show the banner to EU visitors and can configure the banner to do so by changing the  gdprAppliesGlobally variable to false in the tag above (that variable is separate from the window.didomiConfig variable).<br>
      Please note that if you are an EU-based company then you must collect consent and display the banner to all visitors, no matter where they are from.</td>
    </tr>
    <tr>
      <td>sdkPath</td>
      <td>string</td>
      <td>https://sdk.privacy-center.org/</td>
      <td>Path to load the SDK from. This can be used to load the Didomi SDK from your own custom domain after <a href="https://developers.didomi.io/cmp/web-sdk/self-hosting">setting up a reverse proxy</a>. The property must start with <code>http://</code>, <code>https://</code>, or <code>//</code>. It must also end with a final <code>/</code>.</td>
    </tr>
    <tr>
      <td>embedTCFStub</td>
      <td>boolean</td>
      <td><code>true</code></td>
      <td>Define whether the IAB TCF stub is embedded on the page before loading the SDK. If your consent notice uses the IAB TCF, we recommend embedding the IAB TCF stub to optimize the communication with vendors.</td>
    </tr>
    <tr>
      <td>onReady</td>
      <td>function</td>
      <td></td>
      <td>Called when the SDK is loaded. Pass the Didomi object as parameter. Please see the https://developers.didomi.io/cmp/web-sdk/reference for more information about what you can do with the Didomi object</td>
    </tr>
    <tr>
      <td>onConsentChanged</td>
      <td>function</td>
      <td></td>
      <td>Called when a consent is given or withdrawn by the user. Pass the CWT Token as parameter.</td>
    </tr>
    <tr>
      <td>onNoticeShown</td>
      <td>function</td>
      <td></td>
      <td>Called when the notice is shown</td>
    </tr>
    <tr>
      <td>onNoticeHidden</td>
      <td>function</td>
      <td></td>
      <td>Called when the notice is hidden</td>
    </tr>
    <tr>
      <td>onNoticeBackdropclick</td>
      <td>function</td>
      <td></td>
      <td>Called when the backdrop from the popup notice is clicked</td>
    </tr>
    <tr>
      <td>onNoticeClickAgree</td>
      <td>function</td>
      <td></td>
      <td>Called when user clicks on agree on the notice</td>
    </tr>
    <tr>
      <td>onNoticeClickMoreInfo</td>
      <td>function</td>
      <td></td>
      <td>Called when user clicks on learn more on the notice</td>
    </tr>
    <tr>
      <td>onPreferencesClickAgreeToAll</td>
      <td>function</td>
      <td></td>
      <td>Called when user clicks on agree to all on the preferences popup</td>
    </tr>
    <tr>
      <td>onPreferencesClickDisagreeToAll</td>
      <td>function</td>
      <td></td>
      <td>Called when user clicks on disagree to all on the preferences popup</td>
    </tr>
    <tr>
      <td>onPreferencesClickPurposeAgree</td>
      <td>function</td>
      <td></td>
      <td>Called when user agree to a purpose on the preferences popup. (purposeId provided as a parameter)</td>
    </tr>
    <tr>
      <td>onPreferencesClickPurposeDisagree</td>
      <td>function</td>
      <td></td>
      <td>Called when user disagree to a purpose on the preferences popup. (purposeId provided as a parameter)</td>
    </tr>
    <tr>
      <td>onPreferencesClickViewVendors</td>
      <td>function</td>
      <td></td>
      <td>Called when user clicks on view vendors on the preferences popup</td>
    </tr>
    <tr>
      <td>onPreferencesClickSaveChoices</td>
      <td>function</td>
      <td></td>
      <td>Called when user saves his choice on the preferences popup</td>
    </tr>
    <tr>
      <td>onPreferencesClickVendorAgree</td>
      <td>function</td>
      <td></td>
      <td>Called when user agree to a vendor on the preferences popup. (vendorId provided as a parameter)</td>
    </tr>
    <tr>
      <td>onPreferencesClickVendorDisagree</td>
      <td>function</td>
      <td></td>
      <td>Called when user disagree to a vendor on the preferences popup. (vendorId provided as a parameter)</td>
    </tr>
    <tr>
      <td>onPreferencesClickVendorSaveChoices</td>
      <td>function</td>
      <td></td>
      <td>Called when user saves his choice on the vendors view on the preferences popup</td>
    </tr>
  </tbody>
</table>

### Configuration object (Optional)

The notice is usually configured through the Didomi Console. If you choose to manage the configuration via a configuration object, the `config` prop allows you to pass configuration options that override the configuration from the Console and is optional.

This is the structure of the configuration object passed to the `config` prop. For more information, please visit our [SDK documentation](https://developers.didomi.io/cmp/web-sdk/getting-started).

```js
{
  app: {
    ignoreCountry: true,
    privacyPolicyURL: 'http://example.com',
    name: 'Example',
    apiKey: '<Your API key>',
    logoUrl: 'http://logo.png',
    vendors: {
      iab: { // You either choose the option 'all', with optionaly 'exclude', or the 'include' option where you add the vendors manually
        all: true,
        exclude: [1],
        // OR
        include: [3],
      },
      didomi: ['google'],
      custom: [
        {
          id: 'custom-vendor', // Unique ID for the vendor
          name: 'Custom Vendor', // Display name of the vendor
          purposeIds: ['cookies'], // List of purposes that you want to collect consent for, for this vendor
          policyUrl: 'http://www.vendor.com/privacy-policy' // URL to the privacy policy of the vendor
        }
      ]
    },
    customPurposes: [
      {
        id: 'my_custom_purpose',
        name: {
          en: 'My custom purpose',
        },
        description: {
          en: 'Description',
        }
      }
    ]
  },
  languages: {
    enabled: ['en', 'fr', 'es', 'nl', 'ca', 'it', 'de', 'pt'], // List of languages that visitors can use
    default: 'fr', // Default language to use if the visitor uses a language that is not enabled
  },
  notice: {
    position: 'popup',
    closeOnClick: true,
    closeOnClickBackdrop: false,
    daysBeforeShowingAgain: 0,
    textAlignment: 'left',
    learnMorePosition: null,
    learnMoreMargin: '20px 0 0 0',
    logoAlignment: 'flex-start',
    content: {
      popup: {
        en: 'Text',
      },
      notice: {
        en: 'Text',
      },
      dismiss: {
        en: 'Text',
      },
      learnMore: {
        en: 'Text',
      }
    }
  },
  preferences: {
    defaultChoice: true,
    enableAllButtons: true,
    content: {
      text: {
        en: 'Text',
      },
      title: {
        en: 'Text',
      },
      disagreeToAll: {
        en: 'Text',
      },
      agreeToAll: {
        en: 'Text',
      },
      save: {
        en: 'Text',
      },
      textVendors: {
        en: 'Text'
      },
      subTextVendors: {
        en: 'Text'
      }
    },
    information: {
      enable: true,
      content: {
        text: {
          en: 'Text',
        },
        learnMore: {
          en: 'Text',
        },
        agreeAndClose: {
          en: 'Text',
        }
      }
    }
  },
  theme: {
    color: '#3F51B5', // Principal color used by the SDK
    linkColor: '#3F51B5', // Color used for the links in the notice/popup
    font: 'Arial', // Font used by the SDK
    buttons: {
      regularButtons: { // Learn more/disagree/disagree to all buttons.
        backgroundColor: '#eeeeee',
        textColor: '#999999',
        borderColor: 'rgba(34, 34, 34, 0.2)',
        borderWidth: '1px',
        borderRadius: '0px',
      },
      highlightButtons: { // Agree/save/agree to all buttons.
        backgroundColor: 'rgb(194, 39, 45)',
        textColor: '#ffffff',
        borderColor: 'rgba(194, 39, 45, 0.3)',
        borderWidth: '1px',
        borderRadius: '0px',
      }
    }
  },
  tagManager: {
    provider: 'gtm'
  },
  integrations: {
    vendors: { // Setup the integration with Google (ask Didomi to share consent with Google tags)
      google: {
        enable: true,
        eprivacy: true
      }
    },
    refreshOnConsent: true // by default, ads are reloaded after consent is given
  }
  ```


## Example

```jsx
import React, { Component } from 'react'

import { DidomiSDK } from '@didomi/react'

/**
 * This is the configuration object that will set the Didomi SDK
 */
const didomiConfig = {  
  app: {
    name: 'Didomi',
    apiKey: 'API_KEY',
    vendors: {
      iab: {
        all: true,
        version: 2
      }
    }
  },
  notice: {
    position: 'bottom'
  },
  languages: {
    enabled: ['fr', 'en', 'es'],
    default: 'fr'
  }
}


class DidomiDemo extends Component {

  constructor(props) {
    super(props);
    this.didomiObject = {};
  }

  /**
   * Called once we have the callback from the SDK informing that Didoni is loaded and ready
   */
  onDidomiReady(didomi) {
    this.didomiObject = didomi;

    console.log('Didomi Ready - Is the consent required ? : ', this.didomiObject.isConsentRequired());
    console.log('Didomi Ready - Do we have the consent for the vendor IAB 1 : ', this.didomiObject.getUserConsentStatusForVendor(1));
    console.log('Didomi Ready - Do we have the consent for the vendor IAB 1 and the purpose cookies : ', this.didomiObject.getUserConsentStatus('cookies', 1));

  }

  /**
   * Called everytime the consent changes
   */
  consentHasChanged(cwtToken) {
    console.log('Didomi Consent Changed - cwtToken : ', cwtToken);
    console.log('Didomi Consent Changed - Is the consent required ? : ', this.didomiObject.isConsentRequired());
    console.log('Didomi Consent Changed - Do we have the consent for the vendor IAB 1 : ', this.didomiObject.getUserConsentStatusForVendor(1));
    console.log('Didomi Consent Changed - Do we have the consent for the vendor IAB 1 and the purpose cookies : ', this.didomiObject.getUserConsentStatus('cookies', 1));
  }

  render() {
    return <div>
      <h1>Didomi React Demo</h1>
      <DidomiSDK
        iabVersion={2}
        config={didomiConfig}
        gdprAppliesGlobally={true}
        onReady={this.onDidomiReady.bind(this)}
        onConsentChanged={this.consentHasChanged.bind(this)}
      />
      <button onClick={() => this.didomiObject.setUserAgreeToAll()}>Set Agree to All</button>
    </div>
  }
}
  ```

## Customize the notice

You can use your own custom notice to replace the standard Didomi SDK notices (banner or popup). This option keeps some native behaviors like the position of the notice, the backdrop (for the popup notice) or the logic to decide when to display the notice.

Set your HTML in the `notice.content.html` key of the `config` prop:

### Custom React component in the notice

If you want to keep all the advantages of React, you can call our callback function that returns the notice HTML element and render your own React component inside:

  ```jsx
import { render } from 'react-dom'

class NoticeHTML extends Component {
  openPreferences() {
    Didomi.preferences.show()
  }

  render() {
    const noticeStyle = {
      color: 'red'
    }

    return (
      <div style={noticeStyle}>
        <span>Custom Notice HTML. <a onClick={this.openPreferences.bind(this)}>Open Preferences</a></span>
        {
          this.props.shouldDisplayMoreText &&
          <p>More Text</p>
        }
      </div>
    )
  }
}

const didomiConfig = {
  app: {
    apiKey: '<Your API key>',
    notice: {
      content: {
        html: {
          en: element => {
            render(<NoticeHTML shouldDisplayMoreText={false} />, element)
          }
        }
      }
    }
  }
}

...

<DidomiSDK config={didomiConfig}/>
```

Other keys in `notice.content` will be ignored.

### Custom HTML in the notice

You can do everything through HTML:

  ```js
  const didomiConfig = {
  app: {
    apiKey: '<Your API key>',
    notice: {
      content: {
        html: {
          en: '<div>Custom Notice</div>'
        }
      }
    }
  }
}

...

<DidomiSDK config={didomiConfig}/>
  ```

### Didomi SDK Documentation

See [Documentation](https://developers.didomi.io/cmp/web-sdk)

### License

This plugin is [released under the BSD-3 license](LICENSE.md).
