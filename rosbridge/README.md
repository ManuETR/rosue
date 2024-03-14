# How to run a rosbridge server and test its functionality / websocket connection with a browser

Launch rosbridge
`ros2 launch rosbridge_server rosbridge_websocket_launch.xml`


Publish topic
`ros2 topic pub /my_topic std_msgs/String "data: 'Hello world'" -1`


This folder contains a simple website that connects to the rosbridge. Run:

```
npm install
npx webpack
```

Then open the `dist/index.html` file in your browser.