# docker-jmeter
docker jmeter 
# Build docker
clone and make
# Usage
docker run -i --rm -v $(pwd):/root -w /root ted/jmeter /opt/jmeter/bin/jmeter -n -t XXX.jmx -l test_report/XXX.jtl
docker run -i --rm -v $(pwd):/root -w /root ted/jmeter ant -Dxml=report/XXX.xml -Dhtml=test_report/XXX.html