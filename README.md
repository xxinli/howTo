# Tech Stack

Node
React


lerna: https://github.com/lerna/lerna
GraphQL: https://graphql.org/
Apollo: https://www.apollographql.com/docs/react/api/react-apollo
Jest: https://jestjs.io/docs/en/tutorial-react
Knex: https://knexjs.org/
webpack: https://webpack.js.org/

postgreSQL
postico
docker
react-test-renderer


Regex:
Finding Sentences That Contain a Specific Word: /[^.!?]*\bword\b[^.!?]*.?/gi
 e.g /[^.!?]*\bapple\b[^.!?]*.?/gi
  
Replacing Multiple Whitespaces with a Single Whitespace: str.replace(/\s\s+/g, ' ').trim();

const str = "https://en.wikipedia.org/";
str.replace(/[<>|:"*?\\/]+/g, '');    // => "httpsen.wikipedia.org"

Deleting Duplicate Words: 
const str = "This this sentence has has double words.";
str.replace(/\b(\w+)\s+\1\b/gi, '$1');
// => "This sentence has double words."
