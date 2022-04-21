# Redux Essentials Tutorial Example

This project contains the setup and code from the "Redux Essentials" tutorial in the Redux docs ( https://redux.js.org/tutorials/essentials/part-1-overview-concepts ).

The `master` branch has a single commit that already has the initial project configuration in place. You can use this to follow along with the instructions from the tutorial.

The `tutorial-steps` branch has the actual code commits from the tutorial. You can look at these to see how the official tutorial actually implements each piece of functionality along the way.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), using the [Redux](https://redux.js.org/) and [Redux Toolkit](https://redux-toolkit.js.org/) template.

> **Note**: If you are using Node 17, this project may not start correctly due to a known issue with Webpack and Node's OpenSSL changes, which causes an error message containing `ERR_OSSL_EVP_UNSUPPORTED`.  
> You can work around this by setting a `NODE_OPTIONS=--openssl-legacy-provider` environment variable before starting the dev server.
> Details: https://github.com/webpack/webpack/issues/14532#issuecomment-947012063

# NPM으로 실행했음 !

- Social network Feed 컨셉

  22.04.21 리덕스 에센셜 redux 데이터 사용까지. 비동기 논리 및 데이터 가져오기 들어갈 차례.
