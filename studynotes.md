## Breakdown of a URL

URL- uniform resource locator

`https://www.google.com/search?q=the+best_books`

https - protocol
www - sub domanin
google - domain
.com - top level domain
search - path
antything from ? and after - query parameters

read up on nslookup

## Network Ports

Computer have virtual ports.

One port can only go to one application

- There are reserved ports. Don't use any of the reserved ports
  21 - file transfer protocol

* Look up the ports that uou recognize, memorize them and avoid them.

### OSI model

<div>
    <table>
     <tr>
        <td><b>Physical </b></td>
        <td><b>Data link</b></td>
        <td><b>Network</b></td>
        <td><b>Transport</b></td>
        <td><b>Session</b></td>
       <td><b>Presentation</b></td>
       <td><b>Application</b></td>
     </tr>
     <tr>
        <td><b>Fibre coax</b></td>
        <td><b>Ethernet WLAN</b></td>
        <td><b>IPV4 IPV6</b></td>
        <td><b> TCP UDP</b></td>
        <td><b>HTTP TLS DNS</b></td>
        <td><b>HTTP TLS DNS</b></td>
          <td><b>HTTP TLS DNS</b></td>
        </tr>
    </table>
    </div>

## TCP - Transmisson control protocol

TCP (Transmission Control Protocol) is a connection-oriented protocol that guarantees reliable data delivery. It establishes a connection between two devices before sending data and breaks the connection once the data transfer is complete. TCP also provides mechanisms for error detection and correction, ensuring that data arrives intact.
It is used to send packets over a network. A request is sent by client, the data is sent, an acknowledgement of receiving the data is sent by the client. It is reliable, ordered and has error checked data delivery.

## UDP user datagram protocol

UDP (User Datagram Protocol) is a connectionless protocol that is faster and less overhead than TCP. It does not establish a connection before sending data, making it more suitable for applications that require real-time data transmission, such as streaming audio or video. However, UDP does not guarantee reliable data delivery, meaning that data packets may be lost or arrive out of order.
simple, fast data delivery
uses IP to deliver data over networks

### UDP headers

- Source port
- Destination port
- Length
- Cheksum
- Data

## IP internet protocol

(Internet Protocol) is responsible for addressing and routing data packets across the network. It assigns unique IP addresses to devices, allowing them to identify each other and send data to the correct destination. IP also determines the best path for data packets to travel, ensuring that they reach their destination efficiently.
TCP and UDP works over IP
Delivers data packets from source to destination

- TCP over IP

# WebRTC

WebRTC (Web Real-Time Communication): WebRTC is a protocol that enables real-time peer-to-peer communication between web browsers. It is used for applications such as video conferencing, voice chat, and screen sharing. WebRTC is a powerful protocol that can be used to create a wide variety of real-time applications.

### Read up http

HTTPS - HTTP over TLS

http 1.1 - seperate connect, single data - this is what we use today
http 2 - resuse single connection, multiple data

http 2 will be the future version.

## Network protocol

Protocols are the ways that we get to the resources that we need.

## HTTP headers
