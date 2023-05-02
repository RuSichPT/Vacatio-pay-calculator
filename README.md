# Vacation-pay-calculator

## �����
�������� ������ **RESTfull API service** ������������ ����� "����������� ���������"

## �������������� ����������
- Java 11
- Spring Boot
- Maven
- Lombok
- Swagger (Open API)

### API
    GET api/v1/calculate/{avgSalary}/{numDays}/{startDate}

avgSalary - ������� �������� �� 12 �������  
numDays - ���������� ���� �������  
startDate (��������������) - ���� ������ �������  

�����: ����� ��������� �� {numDays} ����.  
���� ������� {startDate} ����, �� ��� ������� �� ����������� ���������

��� ����������� �������� � ����������� ���� ������ ���������� ��������� ������  
https://www.isdayoff.ru


### Swagger (Open API):
http://localhost:8080/swagger-ui.html