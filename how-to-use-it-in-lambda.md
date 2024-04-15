# in lambda you can use it as follow

```nodejs

import { getRandomNumber } from '/opt/helpers.js'
import { ZaionsInfo } from '/opt/constants.js'

export const handler = async (event) => {
  // TODO implement
  const response = {
    statusCode: 200,
    body: JSON.stringify('Hello from Lambda!'),
    randomNumber: getRandomNumber(),
    ZaionsInfo
  };
  return response;
};

```
