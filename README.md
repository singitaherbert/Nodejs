# Nodejs
Learning and using Node Js

#Node.Js History

1. 2009- created
2. 2011- npm created
3. 2015- foundation created
   Getting Started with Node

- Node is a runtime environment for executing JS code.
- Essentially, Node is a C++ program that embeds Chrome’s v8 engine, the fastest
JS engine in the world.
- We use Node to build fast and scalable networking applications. It’s a perfect
choice for building RESTful services.
- Node applications are single-threaded. That means a single thread is used to
serve all clients.
- Node applications are asynchronous or non-blocking by default. That means
when the application involves I/O operations (eg accessing the file system or the
network), the thread doesn’t wait (or block) for the result of the operation. It is
released to serve other clients.
- This architecture makes Node ideal for building I/O-intensive applications.
- You should avoid using Node for CPU-intensive applications, such as a video
encoding service. Because while executing these operations, other clients have
to wait for the single thread to finish its job and be ready to serve them.
- In Node, we don’t have browser environment objects such as window or the
document object. Instead, we have other objects that are not available in
browsers, such as objects for working with the file system, network, operating
system, etc.

# Check If Node installed
- type in cmd Node -v (if not installed)
  *Visit following website to download*

  https://nodejs.org/en*

# Use VS Code to Practise

- Use Exercise Files *(Use to practise Do not copy or reproduce)*
  
# For more refer to the following courses:
  # https://www.linkedin.com/learning/node-js-essential-training-14888164?trk=share_android_course_learning&shareId=kfH9MgqtSsKbl2eOiS79rQ%3D%3D
  # https://codewithmosh.com/p/the-complete-node-js-course


  
