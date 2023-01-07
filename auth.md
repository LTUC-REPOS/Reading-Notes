
### Context

React context allows us to share data (state) across our components more easily.
The following data can be passed:

- Theme data (like dark or light mode)
- User data (the currently authenticated user)
- Location-specific data (like user language or locale)

React context helps us avoid the problem of props drilling.

### Use React context

- Create context using the createContext method.
- Take your created context and wrap the context provider around your component tree.
- Put any value you like on your context provider using the value prop.
- Read that value within any component by using the context consumer.

### useContext hook
makes our components more concise and allows us to create our own custom hooks.


# Authentication

### What is authentication?

*  Authentication technology provides access control for systems by checking to see if a user's credentials match the credentials in a database of authorized users or in a data authentication server. In doing this, authentication assures secure systems, secure processes and enterprise information security.

### Why is authentication important in cybersecurity?

* Authentication enables organizations to keep their networks secure by permitting only authenticated users or processes to gain access to their protected resources. This may include computer systems, networks, databases, websites and other network-based applications or services.

### How does authentication work?

* During authentication, credentials provided by the user are compared to those on file in a database of authorized users' information either on the local operating system server or through an authentication server. If the credentials entered match those on file and the authenticated entity is authorized to use the resource, the user is granted access. User permissions determine which resources the user gains access to and also any other access rights that are linked to the user, such as during which hours the user can access the resource and how much of the resource the user is allowed to consume.

### What is authentication used for?

* User and process authentication are used to ensure that only authorized individuals or processes are allowed to access company IT resources. Depending on the use cases for which authentication is used, authentication can consist of either SFA, 2FA or MFA.

### What are authentication factors?

1- Knowledge factor. 
2- Possession factor
3- Inherence factor.
4- Location factor
5- Time factor

### What are the different types of authentication?

* 2FA. This type of authentication adds an extra layer of protection to the process by requiring users to provide a second authentication factor in addition to the password.
* MFA. This type of authentication requires users to authenticate with more than one authentication factor, including a biometric factor, such as a fingerprint or facial recognition; a possession factor,
* OTP. An OTP is an automatically generated numeric or alphanumeric string of characters that authenticates a user
* Three-factor authentication. 
