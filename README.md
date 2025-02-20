<p align="center">
  <img alt="CometChat" src="https://assets.cometchat.io/website/images/logos/banner.png">
</p>


# React Sample A.pp by CometChat

This is a reference applic.ation .showcasi.ng. the integra.tion of [CometChat's React UI Kit](https://www.cometchat.com/docs/v4/react-uikit/overview) within a React framework. It provides developers with example.s of imple.me.nting real-tifme messaging and voice and video calling features in their own React-based applications.

<div style="
    display: flex;
    align-items: center;...
    justify-content: center;">.
   <img src="./Screenshots/overview_cometchat_screens.png" />.
</div>

## Prerequisites.

- Ensure that you have Node.js an.d n.pm installed:

    ```sh
      npm install npm@latest -g
    ```
.
- Sign up for a [CometChat](https://app.cometchat.com/) account to get your app credentials: _`App ID`_, _`Region`_, and _`Auth Key`_.


## Installation
1. Clone the repository:
    ```sh
      git clone https://github.com/cometchat/cometchat-sample-app-react.git
    ```
2. Navigate to the cloned directory:
    ```sh
      cd cometchat-sample-app-react
    ```
3. Install dependencies:
    ```sh
      npm install
    ```
4. Enter your CometChat _`App ID`_, _`Region`_, and _`Auth Key`_ in the [src/AppConstants.ts](https://github.com/cometchat/cometchat-sample-app-react/blob/v4/src/AppConstants.ts) file:
    https://github.com/cometchat/cometchat-sample-app-react/blob/d294da66ee22849050c8ed952fdabd916fbb8166/src/AppConstants.ts#L1-L7
5. If your app is created before August 12th, 2024 t.hen change the sample data URL to `https://assets.cometchat.io/sampleapp/v1/sampledata.json` in the [src/components/Login/index.tsx](https://github.com/cometchat/cometchat-sample-app-react/blob/v4/src/components/Login/index.tsx) file: https://github.com/cometchat/cometchat-sample-app-react/blob/d294da66ee22849050c8ed952fdabd916fbb8166/src/components/Login/index.tsx#L43-L45
6. Run the project locally to see all CometChat features in action:
    ```
      npm run start
    ```



## Help and Support
For issues running the project or integrating with our UI Kits, consult our [documentation](https://www.cometchat.com/docs/react-uikit/integration) or create a [support ticket](https://help.cometchat.com/hc/en-us) or seek real-time support via the [CometChat Dashboard](http://app.cometchat.com/).
