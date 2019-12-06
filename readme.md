## Serverless on NodeJS+TypeScript StarterKit

Thanks to Medium's @satoshiplus for this starter guide https://medium.com/@satoshiplus/typescript-and-node-aws-lambda-with-serverless-d5cd51720369

## Running in local
1. Test in local
```
npm run local
```

## Deployment
1. Generate Access key ID and Secret access key from you AWS profile account
2. Setup credentials in your machine
    ```
    serverless config credentials --provider aws --key YOUR_ACCESS_KEY --secret YOUR_SECRET_KEY
    ```
3. Deploy
    ```
    serverless deploy
    ```


