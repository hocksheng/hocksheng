# Database

| Brand | Environment | DB identifier                | Role    | ConnectionString                                                      | Port | Bastion IP (Host For local dev) | HAProxy Port (For local dev) |
|-------|-------------|------------------------------|---------|-----------------------------------------------------------------------|------|---------------------------------|------------------------------|
| ind91 | staging     | ind91-staging                | Primary | ind91-staging.c4nqkcmymi9b.ap-east-1.rds.amazonaws.com                | 3306 | 18.166.68.131                   | 3307                         |  
| ind91 | staging     | ind91-staging-read-replica-1 | Replica | ind91-staging-read-replica-1.c4nqkcmymi9b.ap-east-1.rds.amazonaws.com | 3306 | 18.166.68.131                   | 3306                         |   
| ind91 | production  | ind91-prod                   | Primary | ind91-prod.c6qcq9cytjgp.ap-east-1.rds.amazonaws.com                   | 3306 | 16.163.99.236                   | 3306                         |      
| ind91 | production  | ind91-prod-read-replica-1    | Replica | ind91-prod-read-replica-1.c6qcq9cytjgp.ap-east-1.rds.amazonaws.com    | 3306 | 16.163.99.236                   | 3320                         |  
| ind91 | production  | lottery-prod                 | Primary | lottery-prod.c6qcq9cytjgp.ap-east-1.rds.amazonaws.com                 | 3306 | 16.163.99.236                   | 3307                         |   
| bra99 | staging     | bra99-stg                    | Primary | bra99-stg.cb64moogowy9.sa-east-1.rds.amazonaws.com                    | 3306 | 15.228.193.225                  | 3307                         | 
| bra99 | staging     | bra99-stg-read-replica-1     | Replica | bra99-stg-read-replica-1.cb64moogowy9.sa-east-1.rds.amazonaws.com     | 3306 | 15.228.193.225                  | 3306                         |   
| bra99 | production  | bra99-prod                   | Primary | bra99-prod.cb64moogowy9.sa-east-1.rds.amazonaws.com                   | 3306 | 18.230.21.156                   | 3306                         | 
| bra99 | production  | bra99-prod-read-replica-1    | Replica | bra99-prod-read-replica-1.cb64moogowy9.sa-east-1.rds.amazonaws.com    | 3306 | 18.230.21.156                   |                              |


<table>
<tr>
<th>ind91 staging</th>
<th>ind91 production</th>
<th>ind91 lottery production</th>
</tr>
<tr>

<td>

| User                 |       Password       | 
|----------------------|----------------------|
| admin                | bxeLQoBipLo532STF    |
| programuser          | 123456               |
| programuser-readonly | 123456               |

</td><td>

| User                 |       Password       |
|----------------------|----------------------|
| dadmin               | PJc5RAC548Kz3vBcpCkt |
| programuser          | PJc5RAC548Kz3vBcpCkt |
| dereadonly           | JGWfMVsr3osy         |

</td><td>

| User                 |       Password       |
|----------------------|----------------------|
| admin                | 57vfnKZetjUU6d62cwSi |

</td></tr> </table>

<table>
<tr>
<th>bra99 staging</th>
<th>bra99 production</th>
</tr>
<tr>

<td>

| User                 |       Password       |
|----------------------|----------------------|
| admin                |                      |
| programuser          | 123456               |
| programuser-readonly | 123456               |

</td><td>

| User                 |       Password       |
|----------------------|----------------------|
| admin                | dnFd9Gl06a1mNlmB8Pcw |
| dereadonly           | WKLY9uErrvaj         |

</td></tr> </table>







