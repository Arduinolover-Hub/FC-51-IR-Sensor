# FC 51 IR Sensor
In this tutorial we are going to learn about how to make our onw FC-51 IR Sensor, that you can work with Arduino for your project as well. Let's get started.

## FC-51
The FC 51 infrared sensor, it’s a module used to detect if something is passing by or an obstacle is nearby, like in obstacle avoidance robot, this module is very easy to use, it sends infrared waves and if there’s something on the way they reflect back and it’s detected by the receiver, and it depends of how you set the module potentiometer (blue component below) to adjust the detection range.

### Applications
 - Obstacle avoidance in robots
 - Production counting on assembly lines
 - Presence detection
 - Security systems

### Features
LM393 Comparator based detetction circuit is very stable and accurate
On board potentiometer sets obstacle detection range
On board Power LED indicator
On board Obsatcle Detection LED indicator
3.0MM mounting hole for easy mounting the sensor.
Male header for easy connection
Good Accuracy: By use of Infra-red LED transmitter the module performs well in Ambient light
Technical Specifications
Model Number: FC-51
Detection angle: 35 °
Operating Voltage: 3.0V – 6.0V
Detection range: 2cm – 30cm (Adjustable using potentiometer)
pcb size : 3.1 cm (L) x 1.4 cm (W)
Overall Dimension: 4.5cm (L) x 1.4 cm (W), 0.7cm (H)
Ative output level: Outputs Low logic level when obstacle is detected
In-active output level: Outputs High logic level when obstacle is not detected

### Current Consumption:

at 3.3V : ~23 mA
at 5.0V: ~43 mA
Current Consumption:
at 3.3V : ~23 mA
at 5.0V: ~43 mA

### Pinouts
VCC: 3.3V-5V power input pin
GND: 0V power pin
OUT: Digital Output Pin

## Schematic Diagram
The first thing that We need to consider in the PCB process in the schematic diagram, attached you will find the orignal schematic diagram with the components used for the board, We made again the schematic from the Arduino schematic website.

## PCB LAYOUT
Before We continue with the PCB layout, it is important to indicate that You can use any software for PCB Desing, believe me there are many options, even if you use the best software it will not mean that you are the best pcb desinger, so in this case We are going to use Proteus highly recommended if you want to enter in the pcb design world like a professional.

So after We finished and check our schematic circuit We need to switch from schematic to PCB layout. We can see the PCB with the Ground Plane, this helps for noise filter on the pcb. Also is important to remember that in the case of the microcontroller is necesary to place the crystal and the capacitor the closest possible.

Here after we finish the pcb layout We can get the Gerber files, there are two kind of gerber files we have to pay attention to it, the first GerberX2 and the other Gerber RS274X, most of the manufacturer use the second one Gerber RS274X, in some software we will just GerberX2 and Gerber (In the case of Proteus).

There are two kind of gerber files we have to pay attention to it, the first isGerberX2 and the other Gerber RS274X, most of the manufacturer use the second one Gerber RS274X

## 3D MODEL
One of the features of Altium Designer is the 3D visualization, the 3d visualization is important and it give us the posibility to see and check our PCB and how it would be in real, also it can show us the components distribution and dimensions. Before I did not consider this feature so important, but the 3d visualization can show us if our footprint dimensions are ok, if all the components will be places without touching each other by mistake.

► Also very important to remember, if you are going to add 3d models, be carefull that you add in the Step AP214 format, the others extensions and formats can not work correctly.

The 3d visualization can show us if our footprint dimensions are ok, if all the components will be places without touching each other by mistake.

## PDF 3D
According to the software that you are using, You can also get the 3d Models, as I commented you before, this board was desinged On the Altium Designer Software who has this nice option to get the 3d pdf, so later you can share with your coworkers or clients to show the advances of the pcb, without the software installed.

## PCB MANUFACTURE
Once we finished our development board; it is time to bring it to life. In order to manufacture our board, We are going to use JLCPB Services.In case that you do not have an account yet, check out the bellow link

►JLCPCB: https://jlcpcb.com/IAT

Let's bring our Pcb to life with JLCPCB manufacturer

### How to Order our PCB in JLCPCB ?
Once We are register, and We logged in our account, We are ready to submit an order and receive our board in a very short time. In this case We need to update first the gerber files, which contains all the necesary information to build the pcb, You can get the gerber files in the link bellow.

►GerberFiles:HERE

### Upload your gerber files

### Indicate the features
After the upload of our gerber files, We need to indicate the features of the board, in the next picture you can see the options available.

### Add your shipping address
This part is very important, here you should write your currently address, where you would like to receive your pcb prototypes. It is not common but sometimes very rarely, you will need to pay extra feeds, but as I told you, it is very rarely.

### Make the payment and finish the order
After you indicates this information, We continue with the payment section, These is the section where you can apply your coupons or discount codes. Basically We can complete the paymente by two general ways, Paypal or Credit card.

### Receive your PCB
Days later, 7 days or few more, according to your location and custom broker process, You will receive your pcb prototypes.

## Why JCLPCB?
JLCPCB has been at the fore front of the PCB industry. With over 14-year continuous innovation and improvement based on customers' need, we have been growing fast, and becoming a leading global PCB manufacturer, who provides the rapid production of high-reliability and cost-effective PCBs and creates the best customer experience in the industry.In case that you do not have an account yet, check out the bellow link

►JLCPCB: https://jlcpcb.com/IAT

 - Most Efficient, Economic, Innovative PCB Solutions
 - Higher Quality
 - Lower Cost
 - Faster Delivery

JLCPCB provides a rapid production of high-reliability and cost-effective PCBs and create the best customer experience in the indrustry.

## THANKS
Thank to:

►JLCPCB: https://jlcpcb.com/IAT

