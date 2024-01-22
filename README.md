# Azure DevOps Real Time End To End CI/CD Pipeline

Diagram:

<img width="1009" alt="Screenshot 2024-01-22 at 11 42 17" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/e0ba62bd-78ec-4282-a8f7-9443939f3a93">

We go to Azure Devops:

<img width="784" alt="Screenshot 2024-01-22 at 11 43 59" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/8a4c3790-e61a-44ec-a107-a0656d8c1422">

New repository:

<img width="1359" alt="Screenshot 2024-01-22 at 11 44 56" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/340759dd-2dd4-4f26-a022-d0716eff0f11">

We go to Agent pools (where we configure our own VM onwhich you will buiild the app) an check we have an agent:

<img width="1268" alt="Screenshot 2024-01-22 at 11 45 57" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/e8a07933-0f90-4ce1-bee8-54a61dac1729">

A view of the VM:

<img width="702" alt="Screenshot 2024-01-22 at 11 46 59" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/c27d422a-896f-4dac-b8e6-1ede31f699db">

View of the files in the repository:

<img width="1290" alt="Screenshot 2024-01-22 at 11 47 40" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/0855c99d-98d2-4a59-899e-24f47de84f69">

We start building the pipelines and click Maven:

<img width="1190" alt="Screenshot 2024-01-22 at 11 48 57" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/929605ed-efbf-4f8c-87f8-dbceb06420d1">

We define the artifact name and location:

<img width="834" alt="Screenshot 2024-01-22 at 11 49 56" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/55515872-0adf-46b2-8669-47d5856c8d80">

View of artifacts:

<img width="903" alt="Screenshot 2024-01-22 at 11 50 57" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/282ff9b7-59f5-46e7-800c-0acddafa86c9">

We go to SonarQube:

<img width="930" alt="Screenshot 2024-01-22 at 11 51 38" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/3957a069-a52e-4a72-a2ed-985f8455ea26">

We create a Token in security section that we will use in our piepline: 

<img width="1083" alt="Screenshot 2024-01-22 at 11 52 43" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/d94c4ff6-f8c0-4350-859e-30a2361f2d96">

We add SonarQube in the pipeline:

<img width="938" alt="Screenshot 2024-01-22 at 11 53 59" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/a7d84d16-170d-4c5f-a0cf-09be18c7aad6">

<img width="1200" alt="Screenshot 2024-01-22 at 11 54 40" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/12f4684c-8c98-479e-9ed9-2c8b64cf7cd0">

<img width="1240" alt="Screenshot 2024-01-22 at 11 56 06" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/236383ab-34cc-43e4-a2e7-6f4f5cae5eb1">

We add OWASP Dependency Check (used for security scanning):

<img width="954" alt="Screenshot 2024-01-22 at 11 57 43" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/1da286d0-bfee-4713-bde4-94e997351760">

<img width="1049" alt="Screenshot 2024-01-22 at 11 58 46" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/5f251497-4557-407e-95b8-51f0df4e2cbe">

<img width="1367" alt="Screenshot 2024-01-22 at 11 59 07" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/77ab2945-1b7f-4388-aac0-95802948aa4c">

We add Docker task:

<img width="1132" alt="Screenshot 2024-01-22 at 11 59 49" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/bd10afc7-d14e-4d51-94f8-ed694e174aca">

<img width="879" alt="Screenshot 2024-01-22 at 12 00 55" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/8a0044d0-be64-40a8-94f6-ad151f777265">

<img width="1051" alt="Screenshot 2024-01-22 at 12 01 11" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/d7254004-b4d1-4d75-a738-99bc4b0a2f94">

<img width="1113" alt="Screenshot 2024-01-22 at 12 02 09" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/bef351a8-b480-4223-86fb-14890469bd01">

<img width="981" alt="Screenshot 2024-01-22 at 12 02 50" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/b60cbc81-3cbe-4944-9200-e4f8cc52661f">

<img width="842" alt="Screenshot 2024-01-22 at 12 03 09" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/6f966170-782b-4f51-bc98-b36f5ef6e7cb">

<img width="396" alt="Screenshot 2024-01-22 at 12 03 25" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/13a97132-c285-4496-b134-5f2c0aac3b5f">

To access copy the ID in AWS:

<img width="667" alt="Screenshot 2024-01-22 at 12 04 31" src="https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/assets/106017493/e0a6a40a-aca0-4398-af6c-c6e9cb56f450">

We can login:

https://github.com/redjules/Azure-DevOps-Real-Time-End-To-End-CI-CD-Pipeline/tree/main
