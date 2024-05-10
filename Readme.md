# Домашнее задание к занятию «Введение в Terraform»

### Задание 1

2. в personal.auto.tfvars
3. <img width="600" alt="1" src="https://github.com/Shchu4ka/terraform1/assets/29621873/382aa065-2ea7-4ebf-9ca8-9a264df8455c">
4. ошибки в именах resource "docker_container" отсутствие имени в resource "docker_image"
5. ![image](https://github.com/Shchu4ka/terraform1/assets/29621873/f5f679e7-dfe9-4114-9ec6-87b5656c2091)
6. ![image](https://github.com/Shchu4ka/terraform1/assets/29621873/7207958a-8296-414a-b623-1e613453cb4a)
ключ *-auto-approve* опасен тем, что Terraform автоматически применяет все изменения без вашего подтверждения.
Может пригодиться в процессах непрерывной интеграции и непрерывного развертывания (CI/CD)
8. ![image](https://github.com/Shchu4ka/terraform1/assets/29621873/4731a41b-6f2f-4445-9691-0e4e543644c1)
9. образ nginx:latest не был удален т.к. был указан параметр keep_locally = true
![image](https://github.com/Shchu4ka/terraform1/assets/29621873/12def21b-82bb-4566-91fa-58cbbd9f5286)
![image](https://github.com/Shchu4ka/terraform1/assets/29621873/4e41e692-ffb5-4946-920e-1115eecd7922)
