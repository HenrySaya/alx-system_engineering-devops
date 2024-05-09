# 0x07. Networking basics #0
In this particular project I had the priviledge of having to go through one of my favourite topics which is Networking. The backbone of internet and software at large.
OSI (Open Systems Interconnection) is an abstract model to describe layered communication and computer network design. The idea is to segregate the different parts of what make communication possible.

It is organized from the lowest level to the highest level:
  * The lowest level: layer 1 which is for transmission on physical layers with electrical impulse, light or radio signal
  * The highest level: layer 7 which is for application specific communication like SNMP for emails, HTTP for your web browser, etc

![OSI model](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/4e6a0ad87a65d7054248.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240509%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240509T192516Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b2770f85be66c9392cd5f6aaec0b1319b327c20b4bc1bcafcc8ec9cbe8219e60)

In this project I mainly focused on:
  * The Transport layer and especially TCP/UDP
  * On the Network layer with IP and ICMP

## Tasks :page_with_curl:

* **0. OSI model**
  * Questions:
	* What is the OSI model?
		1. Set of specifications that network hardware manufacturers must respect
		2. The OSI model is a conceptual model that characterizes the communication functions of a telecommunication system without regard to their underlying internal structure and technology
		3. The OSI model is a model that characterizes the communication functions of a telecommunication system with a strong regard for their underlying internal structure and technology
	* How is the OSI model organized?

		1. Alphabetically
		2. From the lowest to the highest level
		3. Randomly
  * [0-OSI_model](./0-OSI_model): contains answers to the above questions
