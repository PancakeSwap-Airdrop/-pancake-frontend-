#{
  "name": "pancake-frontend",
  "version": "0.1.0",
  "private": true,
  "scripts": {
    "scripts": {
    "analyze": "source-map-explorer 'build/static/js/*.js'",
    "start": "react-scripts start",
    "build": "CI=false react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject",
    "lint": "eslint 'src/**/*.{js,jsx,ts,tsx}'",
    "format:check": "prettier --check --loglevel error 'src/**/*.{js,jsx,ts,tsx}'",
    "format:write": "prettier --write 'src/**/*.{js,jsx,ts,tsx}'",
    "generate:config": "ts-node --compiler-options '{\"module\":\"commonjs\"}' scripts/generateConfig"
  },
  "husky": {
    "hooks": {
      "pre-commit": "yarn format:check",
      "commit-msg": "commitlint -E HUSKY_GIT_PARAMS"
    }
  },
  "browserslist": {
    "production": [
      ">0.2%",
      "not dead",
      "not op_mini all"
    ],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  "scripts": {
  },
  "dependencies": {
    "@binance-chain/bsc-connector": "^1.0.0",
    "@ethersproject/abi": "^5.0.7",
    "@pancakeswap/uikit": "^0.29.4",
    "@reduxjs/toolkit": "^1.5.0",
    "@types/react": "^17.0.2",
    "@types/react-dom": "^17.0.1",
    "@types/react-router-dom": "^5.1.5",
    "@types/styled-components": "^5.1.7",
    "@web3-react/core": "^6.1.9",
    "@web3-react/injected-connector": "^6.0.7",
    "@web3-react/walletconnect-connector": "^6.1.9",
    "bignumber.js": "^9.0.0",
    -confetti": "^1.3.3",
    "chart.js": "^2.9.4",
    "date-fns": "^2.17.0",
    "ethers": "^5.0.31",
    "graphql": "^15.5.0",
    "graphql-request": "^3.4.0",
    "js-cookie": "^2.2.1",
    "lodash": "^4.17.20",
    "node-fetch": "^2.6.1",






    
    "react": "^17.0.1",
    "react-chartjs-2": "^2.11.1",
    "react-countup": "^4.3.3",
    "react-dom": "^17.0.1",
    "react-feather": "^2.0.8",
    "react-helmet-async": "^1.0.9",
    "react-redux": "^7.2.2",
    "react-router-dom": "^5.2.0",
    "react-scripts": "^4.0.1",
    "react-transition-group": "^4.4.1",
    "styled-components": "^5.1.1",
    "swiper": "^6.5.0",
    "typescript": "^4.1.5",
    "web3": "^1.3.5"
  },
  "devDependencies": {
    "@commitlint/cli": "^11.0.0",
    "@commitlint/config-conventional": "^11.0.0",
    "@pancakeswap/eslint-config-pancake": "^1.0.1",
    "@types/jest": "^26.0.19",
    "@types/react-redux": "^7.1.16",
    "@types/react-transition-group": "^4.4.1",
    "eslint": "^7.20.0",
    "husky": "4.3.5",
    "prettier": "^2.1.2",
    "source-map-explorer": "^2.5.2",
    "ts-node": "^9.1.1"
  }
}
 -pancake-frontend-
