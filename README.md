# fetch-response-json
json response for fetch

## install
npm i fetch-response-json

## usage
    import fetchResponseJson from 'fetch-response-json';

    fetch('/endpoint')
      .then(fetchResponseJson)
      .then(data => console.log(data));
