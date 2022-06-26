# stompjs-vite

A modified StompJS client that works with the Vite compiler


## Download the file and place in your src folder somewhere like a /lib folder

```
import Stomp from '@/lib/stomp.js';
const socket = new SockJS(SOCKET_ENDPOINT);
const stompClient = Stomp.over(socket);
 
```
