# SC-300
Guía de estudio SC-300


> Your existing guest users won't be affected if you enable email one-time passcode, as your existing users are already past the point of redemption. Enabling email one-time passcode will only affect future redemption activities where new guest users are redeeming into the tenant."


![image](https://github.com/gecr07/SC-300/assets/63270579/2a140963-18eb-4e90-8c57-d052fd6c2648)


![image](https://github.com/gecr07/SC-300/assets/63270579/9ecdb732-d58d-4392-86c5-19a84554d6d6)

![image](https://github.com/gecr07/SC-300/assets/63270579/f038d657-12d9-49c0-b3cb-18843bf77c20)

![image](https://github.com/gecr07/SC-300/assets/63270579/5ef912e2-136b-4b5f-9122-9218324ec4b2)



![image](https://github.com/gecr07/SC-300/assets/63270579/6232e195-a172-4cbd-9ee4-7689e81154b5)


![image](https://github.com/gecr07/SC-300/assets/63270579/f39e1c52-6b85-4a5c-b241-b000ce58ce09)


![image](https://github.com/gecr07/SC-300/assets/63270579/5ee74165-a700-49c7-9acf-17ee257d7ce1)

> All objects that you want to synchronize must be direct members of the group. Users, groups, contacts, and computers or devices must all be direct members. Nested group membership isn't resolved. When you add a group as a member, only the group itself is added. Its members aren't added."

![image](https://github.com/gecr07/SC-300/assets/63270579/c1290756-a9e5-408e-8c32-5b2d159c21c8)


![image](https://github.com/gecr07/SC-300/assets/63270579/5a55103f-863e-4254-ae66-fc0ebd81d4da)


## Cloud device administrator

> Cloud device administrator an enable, disable, and delete devices in Azure AD and read Windows 10 BitLocker keys in the Azure portal. The role does not grant permissions to manage any other properties on the device.

## Azure Joined devices vs Registered Devices

![image](https://github.com/gecr07/SC-300/assets/63270579/d7035d6e-caca-4c17-821c-d2c8775b5849)


![image](https://github.com/gecr07/SC-300/assets/63270579/9e78c225-f688-4087-9955-1e268282254a)

## Trusted IPs Trusted Locations

> The biggest difference is the location of the configuration. Trusted IPs is a feature configuration of multi-factor authentication, while named locations is a feature configuration of conditional access


## Trusted IP = Legacy MFA setting.
## Named Location = Conditional Access setting.


##  sign in risk police vs user risk policy

> User risk (represents the probability that a given identity or account is compromised.) Sign-in risk (represents the probability that a given authentication request isn't authorized by the identity owner.)

![image](https://github.com/gecr07/SC-300/assets/63270579/39d651e8-a6fc-4ca3-91a1-992b0673cb0c)

## Azure Seamless Single Sign-on 

permite iniciar sesión en Azure AD automáticamente en equipos y redes corporativas. Esta característica gratuita proporciona a los usuarios un fácil acceso a las aplicaciones sin necesidad de componentes locales.

## User Administrato

manage license assignments and reset user passwords.

![image](https://github.com/gecr07/SC-300/assets/63270579/33936ebd-bc99-4a7d-afa3-625972a06534)


![image](https://github.com/gecr07/SC-300/assets/63270579/e87c1102-e5b2-48ae-a52b-6e2d5bde5868)

![image](https://github.com/gecr07/SC-300/assets/63270579/5afe1012-72cd-4cdb-92b3-635e8c6446dc)

![image](https://github.com/gecr07/SC-300/assets/63270579/e0cb86b3-b982-4109-9121-8f7cdc79b822)


## What is Application Proxy?

Application Proxy is a feature of Azure AD that enables users to access on-premises web applications from a remote client. Application Proxy includes both the Application Proxy service which runs in the cloud, and the Application Proxy connector which runs on an on-premises server. Azure AD, the Application Proxy service, and the Application Proxy connector work together to securely pass the user sign-on token from Azure AD to the web application.

![image](https://github.com/gecr07/SC-300/assets/63270579/f1b5f6ea-a548-42cf-885c-03d6b99a8496)

![image](https://github.com/gecr07/SC-300/assets/63270579/8ccfd717-d405-4d6c-9a8d-edda82d19a70)

![image](https://github.com/gecr07/SC-300/assets/63270579/78352342-6699-4dd5-adb9-ac39c9a27336)

![image](https://github.com/gecr07/SC-300/assets/63270579/307d22d6-6cb7-4fd3-ad8a-03aa0609e6cf)

![image](https://github.com/gecr07/SC-300/assets/63270579/6a6dde6b-cc74-4781-b3e0-1987ab2099cf)

## Un service principal ( osea es una identidad)

de tipo aplicación se crea para que sea empleada en representación de una aplicación. Siendo una identidad única y específica para el tenant en el que funcionará.

## Managed identity 

habilita la autenticación de servicios en Azure AD mientras que RBAC habilita la autorización en los servicios. Combinando las dos tendremos servicios que pueden autenticarse y servicios que autorizan su uso a diferentes niveles a los servicios autenticados.

![image](https://github.com/gecr07/SC-300/assets/63270579/3ec5c22a-a51e-4406-9066-68e758faaa44)

![image](https://github.com/gecr07/SC-300/assets/63270579/97db0343-b96d-4665-afea-543d27c24935)

> Managed identities for Azure resources is the new name for the service formerly known as Managed Service Identity (MSI).

NO se pueden asignar managment identityes ni a cosas on premise ni a grupos dinamicos. A y me falto solo se pueden asignar a Security groups.


## Grupos reviwers SELF 

> Cuando se requiere que los miembros realicen una auto-revisión, solo aparecerá un usuario en la "Descripción general" para revisar, por lo que solo el Usuario3 podrá revisarse a sí mismo.


## What are access reviews?

Access reviews in Azure Active Directory (Azure AD), part of Microsoft Entra, enable organizations to efficiently manage group memberships, access to enterprise applications, and role assignments. User's access can be reviewed regularly to make sure only the right people have continued acces

## Microsoft Azure AD entitlement management

can help you efficiently manage access to groups, applications, and Microsoft SharePoint Online sites for internal users, and for users outside your organization who need access to those resources. ( access package ).

## The Privileged Authentication Administrator 




## Integrate Azure AD logs with Azure Monitor logs (siemopre que sea algo de integrar AD logs se hace desde Diagnostic settings)



### Azure Workbooks

Son para el analisis d edatos como libros dice ahi canvas pero se usan para anlizar y sacar metricas.


![image](https://github.com/gecr07/SC-300/assets/63270579/d5fcf85c-0081-401a-8ccf-520fb749b332)


## Azure Insights ( casi no se usa)

![image](https://github.com/gecr07/SC-300/assets/63270579/58af096f-18f8-4869-9ac0-86cb074a21bf)

## Microsoft Sentinel data connectors

data connectors to start ingesting your data into Microsoft Sentinel. Microsoft Sentinel comes with many out of the box connectors for Microsoft services, which integrate in real time. For example, the Microsoft 365 Defender connector is a service-to-service connector that integrates data from Office 365, Azure Active Directory (Azure AD), Microsoft Defender for Identity, and Microsoft Defender for Cloud Apps.

## Access packed policy

Es una politica que restringe por ejemplo que usuarios de x dominio puedan acceder a un access packet( este contiene permisos a servicios etc)

## Group owner permissions

![image](https://github.com/gecr07/SC-300/assets/63270579/8ec8f435-19bc-495a-b5f0-c12a4691c3ed)


![image](https://github.com/gecr07/SC-300/assets/63270579/dca49ef5-53ad-4c1e-8b98-22b491178530)

## Contributor Rol ( built in role)


Grants full access to manage all resources, but does not allow you to assign roles in Azure RBAC, manage assignments in Azure Blueprints, or share image galleries.


## Govern access for external users in entitlement management


> Entitlement management uses Azure AD business-to-business (B2B) to share access so you can collaborate with people outside your organization. With Azure AD B2B, external users authenticate to their home directory, but have a representation in your directory. The representation in your directory enables the user to be assigned access to your resources.

![image](https://github.com/gecr07/SC-300/assets/63270579/7269805f-3ed0-4fdc-8496-d8fe190327fa)



![image](https://github.com/gecr07/SC-300/assets/63270579/b3a80936-9aa5-4bc5-817e-9f39cb58b770)


## An administrative unit

An administrative unit can contain only users, groups, or devices.
Administrative units restrict permissions in a role to any portion of your organization that you define.


## Security Groups members

>Dynamic and M365 Groups CANNOT be added to security groups

## Microsoft 365 Groups members

Pueden contener solo usuarios.

> M365 groups cannot contain other groups.

## MFA account lockout

The account lockout settings let you specify how many failed attempts you want to allow before the account becomes locked out.

## Max number of devices

Maximum number of devices: This setting enables you to select the maximum number of Azure AD joined or Azure AD registered devices that a user can have in Azure AD. If users reach this limit, they can't add more devices until one or more of the existing devices are removed. The default value is 50. You can increase the value up to 100. If you enter a value above 100, Azure AD will set it to 100. You can also use Unlimited to enforce no limit other than existing quota limits.

## Create catalogs

 From the Identity Governance blade, modify the Entitlement management settings. 

 ![image](https://github.com/gecr07/SC-300/assets/63270579/5ecb2db5-f7ef-400e-8424-8f70d1d60612)

![image](https://github.com/gecr07/SC-300/assets/63270579/e8670fcc-e4ac-43cd-a5cf-8d3a10f62442)

![image](https://github.com/gecr07/SC-300/assets/63270579/14983f59-df7d-45a8-a500-a482dae1b4e3)

![image](https://github.com/gecr07/SC-300/assets/63270579/596a7c3a-0284-4136-8ec0-7cff7ffc1f2a)

 ## Application Developer

Users in this role can create application registrations when the "Users can register applications" setting is set to No. This role also grants permission to consent on one's own behalf when the "Users can consent to apps accessing company data on their behalf" setting is set to No. Users assigned to this role are added as owners when creating new application registrations.

## Cloud Device Administrator

Users in this role can enable, disable, and delete devices in Azure AD and read Windows 10 BitLocker keys (if present) in the Azure portal. The role does not grant permissions to manage any other properties on the device.

## The Privileged Role Administrator


![image](https://github.com/gecr07/SC-300/assets/63270579/2ce95dd6-69e0-4467-a369-ddc22a020bd5)


## User Administrator 


![image](https://github.com/gecr07/SC-300/assets/63270579/e6bb132e-84f8-4c78-95df-3a0e9ce78a53)



![image](https://github.com/gecr07/SC-300/assets/63270579/071a245e-ca11-460f-9c9d-6a1a50c3359f)

![image](https://github.com/gecr07/SC-300/assets/63270579/894b8e97-358c-41ad-b622-0084e9ade8fa)

![image](https://github.com/gecr07/SC-300/assets/63270579/3337ac02-1fe6-4ee3-b9cb-f77454856bfb)

![image](https://github.com/gecr07/SC-300/assets/63270579/f2a36352-672e-4b44-be65-c8ac30cb22da)


***VPN Access = The Network Policy Server (NPS) extension for Azure allows organizations to safeguard Remote Authentication Dial-In User Service (RADIUS) client authentication using cloud-based Azure AD Multi-Factor Authentication (MFA), which provides two-step verification.***


## Azure Active Directory Password Protection

Users often create passwords that use common local words such as a school, sports team, or famous person. These passwords are easy to guess, and weak against dictionary-based attacks. To enforce strong passwords in your organization, Azure Active Directory (Azure AD) Password Protection provides a global and custom banned password list. A password change request fails if there's a match in these banned password list.

To protect your on-premises Active Directory Domain Services (AD DS) environment, you can install and configure Azure AD Password Protection to work with your on-prem DC. This article shows you how to install and register the Azure AD Password Protection proxy service and ***Azure AD Password Protection DC agent*** in your on-premises environment.

Para hacer que un usuario cabie su passd marcalo como "Compromised".

## Security defauls

![image](https://github.com/gecr07/SC-300/assets/63270579/16d520a2-2e2c-450f-b911-afe5cd622f88)

Para asegurar que tu puedes tener control access a Microsoft 365 resources con condicinal access  tienes que desactivar  los security defaults.

![image](https://github.com/gecr07/SC-300/assets/63270579/2733bc52-bbf1-430b-8d09-7bc0e721fb6a)


![image](https://github.com/gecr07/SC-300/assets/63270579/2b8e617d-6d7f-4570-8f7a-9e7d5fadf538)


![image](https://github.com/gecr07/SC-300/assets/63270579/a125bb8b-735a-4f7d-8504-3c5a0274f63e)

![image](https://github.com/gecr07/SC-300/assets/63270579/eda2279a-bd5b-48e9-955c-862c73f90c5d)

![image](https://github.com/gecr07/SC-300/assets/63270579/cb835e92-998d-4bbe-a055-a69354d3d902)

![image](https://github.com/gecr07/SC-300/assets/63270579/626eb375-8a04-4115-a070-6da73eb09d80)

> N, Y, Y. An administrator scoped to the administrative unit can manage properties of the group, such as group name or membership, but they cannot manage properties of the users or devices within that group (unless those users and devices are separately added as members of the administrative unit). Only Users 1 and 2 are directly added in the AU. ( respuesta correcta )

![image](https://github.com/gecr07/SC-300/assets/63270579/7b845abf-c01a-49f5-8210-24f348d136a7)

![image](https://github.com/gecr07/SC-300/assets/63270579/4d53bd8f-2794-4ac6-8b7e-2e5ba2ab63e8)


> El Privileged authentication administrator no puede configurar metodos de MFA alternativos solo puede quitar el recordar este dispositivo en el MFA solo el Seurity administrator puede de entre estos 3

![image](https://github.com/gecr07/SC-300/assets/63270579/76ce5f6d-55ac-48d0-9b75-9e6d6b43f75b)

## Clues

Magaed identities are not elegible for AD role.

Se puede crear un access review para un rol,grupo,app y un azure ad role.

No se pueden crear access reviews para Devices

A una App1 se le pueden asignar solo grupos de seguridad o 365 groups.

Cuando te hable de "specifically block 'BASIC' Authentication in Exchange Online, not 'LEGACY' Authentication. Microsoft specifically details how to do this here:" Piensa en an application control profile in Microsoft Endpoint Manager.

Solo se puden clonar built-in Azure subscription roles y si hay un rol asociado a eso pues ese!

Terminos y condiciones no aceptados se gestionan mediante condicional access.

![image](https://github.com/gecr07/SC-300/assets/63270579/29898135-574b-4162-ba83-283ec2bede8c)


![image](https://github.com/gecr07/SC-300/assets/63270579/a587e3e9-8421-480b-9981-76cae72db9fa)

![image](https://github.com/gecr07/SC-300/assets/63270579/a172c686-2ee1-4397-a4e8-ddf680decb54)

![image](https://github.com/gecr07/SC-300/assets/63270579/da5144f2-6788-4939-a29a-5995a0992055)


Application Administrator = Can create and manage all aspects of app registrations and enterprise apps.

Cloud Application Administrator = Can create and manage all aspects of app registrations and enterprise apps ***except App Proxy***.

Service Support Administrator = Can read service health information and manage support tickets.

Application Developer = Can create application registrations independent of the 'Users can register applications' setting.

Cuando se trata de banned passwords la unica que hace como el bypass por asi decirlo es cambiar la S por el $ de ahi en fuera captura mayusculas minusculas y @. Asi que la mayoria de los passwrors va a estar banneados. 

## Cloud App Discovery in Microsoft Cloud App Security

> Cloud Discovery analyzes your traffic logs against the Microsoft Defender for Cloud Apps catalog of over 31,000 cloud apps. The apps are ranked and scored based on more than 90 risk factors to provide you with ongoing visibility into cloud use, Shadow IT, and the risk Shadow IT poses into your organization


## All the questions Yes or no ( with the right answer) Todas las que ponga aqui son yes


![image](https://github.com/gecr07/SC-300/assets/63270579/085d7fd6-7435-45da-823d-05991246cd2c)

![image](https://github.com/gecr07/SC-300/assets/63270579/f99b85a9-4256-48d0-a9b5-41341ad71043)

![image](https://github.com/gecr07/SC-300/assets/63270579/e2e93aa5-9fa7-4919-a9bb-03634f39e74c)

![image](https://github.com/gecr07/SC-300/assets/63270579/21f7236c-b4b2-4ffc-83ed-31116410347a)

![image](https://github.com/gecr07/SC-300/assets/63270579/98914f8e-c73b-40ce-9562-d9d20aef1124)

![image](https://github.com/gecr07/SC-300/assets/63270579/7db100a8-cf21-4c2c-aea9-abf9e1616ac1)

![image](https://github.com/gecr07/SC-300/assets/63270579/3f1e064a-a0d2-4add-bf77-f3d10924e6a4)




