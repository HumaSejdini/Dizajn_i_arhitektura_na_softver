Оваа апликаја има два дела, дава посебни проекта.Backedn делот е иплементиран во Springboot користејќи Java.
Frontend делот е во Angular,а за база корситиме mySQL база која е врзна во Spring, во applicatiol.properties. Во моментот 
читаме само основни податоци од базата и ги прикажуваме на рутата за банки.
Излезот од базата е мапиран на localhost:8080/banks, таму Spring предава json од податоци, кои потоа ги обработува Angular.