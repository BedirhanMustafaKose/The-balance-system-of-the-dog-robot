# The-balance-system-of-the-dog-robot.
Köpek Robot Denge Sistemi
4 bacaklı bir robotun sağdan, soldan, önden ve arkadan gelecek basınca karşı eklemlerini kullanarak basınca adapte olacağı, dengede kalacağı bir sistem yaptık. Basıncın rüzgâr olduğunu düşünebilirsiniz. Çalışma prensibini anlatacak olursak sağdan esen bir rüzgar olduğunda robotun sol ayaklarında bulunan hx711'lere bağlı olan load sensörler üzerine düşen basınç artacak ve bu şekilde robot rüzgarın ne taraftan estiğini anlayabilecek ve buna uygun pozisyonu alacak. Robotumuzda load sensörler hx711'lere onlarda slave arduinoya bağlılar. 4 bacaktan da alınan datalar Slave arduino üzerinde toplanıyor ve buradan master arduinoya yollanıyor. Master arduinoda bu datalar karşılaştırılarak robotun yapması gereken hareket belirleniyor ve master arduinoya bağlı olan mg996r servo motorlara komutlar yollanıyor. Robotumuzda 3,7 volt 4Ah ve 7,7 volt 7Ah lik iki bataryamız bulunuyor. 1. batarya arduinolar ve sensörleri beslerken diğer bataryamız motorları beslemekte. Motorları 6 volt ile beslememiz gerektiğinden bir adet dc-dc düşürücümüz var.
The balance system of the dog robot
We have built a system where a 4-legged robot will adapt to the pressure and stay in balance by using its joints against the pressure coming from the right, left, front and rear. You might think that the pressure is the wind. If we explain the working principle, when there is a wind blowing from the right, the pressure falling on the load sensors connected to the hx711s on the left feet of the robot will increase, and in this way, the robot will understand from which direction the wind is blowing and take the appropriate position. In our robot, the load sensors are connected to the hx711s and they are connected to the slave arduino. The data received from all 4 legs are collected on the Slave Arduino and sent to the master Arduino from there. By comparing these data in the master arduino, the action that the robot should make is determined and commands are sent to the mg996r servo motors connected to the master arduino. We have two batteries of 3.7 volts 4Ah and 7.7 volts 7Ah in our robot. While the first battery feeds the arduinos and sensors, the other battery feeds the motors. Since we need to supply the motors with 6 volts, we have a dc-dc converter.
Çizimler için : https://grabcad.com/library/the-balance-system-of-the-dog-robot-1
