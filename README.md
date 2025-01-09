OSI Model

    What it is
    How many layers it has
    How it is organized

What is a LAN

    Typical usage
    Typical geographical size

What is a WAN

    Typical usage
    Typical geographical size

What is the Internet

    What is an IP address
    What are the 2 types of IP address
    What is localhost
    What is a subnet
    Why IPv6 was created

TCP/UDP

    What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)
    What is the main difference between TCP and UDP
    What is a port
    Memorize SSH, HTTP and HTTPS port numbers
    What tool/protocol is often used to check if a device is connected to a network

More Info

The second line of all your Bash scripts should be a comment explaining what is the script doing

For multiple choice question type tasks, just type the number of the correct answer in your answer file, add a new line for every new answer, example:

What is the most important position in a software company?

    Project manager
    Backend developer
    System administrator

QUIZZ

Which of the following statements are correct about HTTPS ?
HTTPS stands for Hypertext Transfer Protocol Secure.
HTTPS is an extended version of HTTP and is used to transfer data in a more secure manner.
In HTTPS the communication is encrypted using the TLS (Transport Layer Security) protocol.
HTTPS port number is 443.

Which of the following statements are correct about HTTP ?
HTTP stands for Hypertext Transfer Protocol.
HTTP is used to transfer data between a server and a client, mainly to browse web pages etc....
HTTP port number is 80.


Given the following code, which class method greating is going to be called ?
class A:
  def greating(self):
    print("Hello from class A")

class B:
  def greating(self):
    print("Hello from class B")


class C(A, B):
  pass


class D(C, B):
  pass

obj = D()
obj.greating()

Answer: The greating() method from the A class.

Given the following code, which class method greating is going to be called ?
class A:
  def greating(self):
    print("Hello from class A")

class B(A):
  def greating(self):
    print("Hello from class B")

class C(B, A):
  pass

obj = C()
obj.greating()

Answer: The greating() method from the B class.

The json.load(file_object) function reads from a file JSON data and parses it into a Python object (usually a dictionary).
TRUE

ABOUT JSON:
JSON stands for Javascript Object Notation.
JSON is a standard file format used mainly for data interchange.

What is data serialisation and what are some of its valid examples ?
Data serialization is the process of converting data objects into a format that can be easily stored, transmitted, or shared across different systems or platforms (like JSON, XML etc...).
Example: from Python dictionary to JSON.
Example: from Javascrip object to XML.

What is data deserialisation and what are some of its valid examples ?
Is the opposite of data serialization.
Example: from JSON to Python Dictionary.

def func(**kwargs):
    // some code here (irrelevant)
    // ...

Answer: The function func can take a variable (changeable) number of keyword arguments.
This is a correct way to use the function func: func(name='James', age=35, job='programmer', level='senior').


    A public IP address is a unique identifier assigned to a device connected to a network that is accessible from the internet. It is assigned by the Internet Service Provider (ISP) and serves as the device's public-facing address.  A private IP address is an identifier assigned to devices within a private network, such as a home or office network. It is used for communication within the local network and is not directly accessible from the internet.
YES

Given the following code, which class method greating is going to be called ?
class A:
  def greating(self):
    print("Hello from class A")

class B(A):
  def greating(self):
    print("Hello from class B")

obj = B()
obj.greating()

Answer: The greating() method from the B class.

About the following functions json.dump() and json.dumps() :
The json.dumps(dict, indent) function converts a Python object to a JSON string.
The json.dump(dict, file) function is used for writing data into a JSON file.

About LAN :
LAN is a type of networks.
LAN stands for Local Area Network.
LAN is used to group computers and machines in the same building (locally).
We can have a working LAN without the need to be connected to the internet.

About the internet :
The word Internet stands for INTERconnected NETwork
The Internet is a WAN.

Given the following code, which class method greating is going to be called ?
class A:
  def greating(self):
    print("Hello from class A")

class B(A):
  def greating(self):
    print("Hello from class B")

class C(B):
  def greating(self):
    print("Hello from class C")

obj = C()
obj.greating()

Answer: The greating() method from the C class.

About the OSI model ?
OSI stands for Open Systems Interconnection.
OSI is the first standard model to be used for networks communication.
OSI consists of 7 layers.

About WAN ?
WAN stands for Wide Area Network.
WAN is a network of networks, it connects different devices and networks located in a very wide range (the internet for example).

About SSH ?
SSH stands for Secure SHell
The port number for SSH is 22

True statements about the usage of TCP and UDP protocols ?
TCP guarantees (in-order) packet delivery, which is why it's heavier and slower than UDP but it's reliable.
UDP doesn't verify data as TCP does, thus it is lighter than it.
UDP is mainly used for Live streaming, online multiplayer gaming and VoIP..
TCP is used for web browsing, FTP, emailing, SSH etc...

the correct statements about the function below :
def func(*argv):
    // some code here (not relevant)
    // ...

The function funccan take a variable (changeable) number of non-keyword arguments.
This is a correct way to use the function func: func("my name ", "is ", "Kyle").
This is a correct way to use the function func: func("hello world").

About TCP/UDP :
TCP stands for Transmission Control Protocol.
UDP stands for User Datagram Protocol.
TCP performs a retransmission of lost packets, thus It's heavier than UDP.
UDP doesn't performs a retransmission of lost packets and it's lighter than TCP.
UDP is faster than TCP.
UDP is a connectionless protocol. Unlike TCP which a connection-oriented that needs to establish a connection before transferring data.

What is a MAC address ?
MAC stand for Media Access Control.
MAC is unique identifier assigned to network interfaces, such as Ethernet or Wi-Fi adapters, by the manufacturer. It is a hardware-based address that provides a unique ID to each device on a network.
