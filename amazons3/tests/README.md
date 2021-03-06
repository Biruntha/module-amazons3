# Ballerina Amazon S3 Connector Test

The Amazon S3 connector allows you to access the Amazon S3 REST API through ballerina.

## Compatibility
| Ballerina Version | Amazon S3 API Version |
|-------------------|---------------------- |
| 0.991.0           | 2006-03-01           |

###### Running tests

1. Create `ballerina.conf` file in `module-amazons3`, with following keys and provide values for the variables.
    
    ```.conf
    ACCESS_KEY_ID=""
    SECRET_ACCESS_KEY=""
    SECURITY_TOKEN="<security_token>"
    REGION=""
    BUCKET_NAME=""
    AMAZON_HOST=""
    ```
2. Navigate to the folder module-amazons3

3. Run tests :

    ```ballerina
    ballerina init
    ballerina test amazons3 --config ballerina.conf
    ```
```