## useId
useId is a React Hook for generating unique IDs that can be passed to accessibility attributes.

const id = useId()
Reference 
useId() 
Call useId at the top level of your component to generate a unique ID:

import { useId } from 'react';

function PasswordField() {
  const passwordHintId = useId();
  // ...

Parameters 
useId does not take any parameters.

Returns 
useId returns a unique ID string associated with this particular useId call in this particular component.




##Refer
https://github.com/hiteshchoudhary/react-english/tree/main/06currencyconverter