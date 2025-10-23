# Antra-React-Assignment-1 Part 1

## Your First Component

1. Export the component
<img width="1470" height="712" alt="image" src="https://github.com/user-attachments/assets/4a1842fa-d82a-48f5-8542-e0071e74246f" />

2.Fix the return statement
<img width="1470" height="712" alt="image" src="https://github.com/user-attachments/assets/e5016a99-b587-4dc5-b063-f01307af0fb8" />

3. Spot the mistake
<img width="1470" height="712" alt="image" src="https://github.com/user-attachments/assets/07e02aca-e370-4c2f-a1de-d74a223fd186" />

4. Your own component
<img width="1470" height="712" alt="image" src="https://github.com/user-attachments/assets/1127e5a5-1cb8-4fac-adec-aad96627ae3b" />

## Importing and Exporting Components
1. Split the components further
<img width="1470" height="712" alt="image" src="https://github.com/user-attachments/assets/adc67594-7723-457a-a6c3-5110c791be71" />

## Writing Markup with JSX
1. Convert some HTML to JSX
   <img width="1470" height="712" alt="image" src="https://github.com/user-attachments/assets/c1f881b1-cf01-4c85-b7b9-71b611accf89" />

## JavaScript in JSX with Curly Braces
1. Fix the mistake
   <img width="1470" height="712" alt="image" src="https://github.com/user-attachments/assets/97403ccc-dd88-4bd4-95c8-96b64e011bfe" />

2. Extract information into an object
   <img width="1470" height="712" alt="image" src="https://github.com/user-attachments/assets/6f268a5e-6881-457f-a04b-df31c5232997" />

3. Write an expression inside JSX curly braces
<img width="1470" height="712" alt="image" src="https://github.com/user-attachments/assets/afb5c872-7b90-425d-9217-3a55e3b616e9" />

# Part 2

1. What is dependency and dev dependency? What’s the difference?
   The dependency includes all the library names on which the project is dependent on like initial the project is dependent only on the react, and react-dom, and as soon as new library is installed it is added to this dependency list in the package.json file and the package-lock.json file. Additionally, the dev dependency are the dependencies or the libraries which are just neede for the development environment and not needed in the prodcution so while installing the libarary using npm we must provide parameter -D.
   
3. What is package.json and package-lock.json? What’s the difference?
   The package.json file has the key value pairs for the project, wherein the bydefault keys are name, scripts, dependencies, and devDependencies. It keeps track of all the packages installed and allows the other users to install the same packages with the same version into their environment. Whereas the package-lock.json file has more indepth details of each packages, and it is not required to understand for the web development.
   
5. What is JSX? Why do we need babel?
   The JSX is the file format which allows to write a HTML code in the Javascript file. So, the JSX is mix of the HTML and Javascript in 1 file, hence the skeleton and the logic resides at the same place. Furthermoew, the JSX is firstly converted to the JS as the web browsersonly understand HTML, CSS, and JavaScript. So, the Babel helps in doing the converstion.
   
7. SPA vs MPA
   SPA stands for the Single Page Application, where in there is only 1 elemnet and the different content is inserted into that tag, this results in the page not getting reloaded everytime when a routing is done to another URL. Whereas the MPA stands for the Multiple Page Application, in which the multiple files are created for every pages like creating the multiplke page using the simple HTML file, and when the redirection is made to another page then the page is reloaded to load the content of that file.
   
9. CSR vs SSR
    CSR | SSR
   1. Client Side Rendering  | Server Side Rendering
   2. HTML, CSS, and JS code is merged and the page is formed in the client browser | The Page is created from the server side and it is sent to the client
   3. The initial loading of a website takes time | The initial loading doesn't take time
   4. Future loading doesn't take much time as the entire code is available to the client | Furture loading might take more time compared to CSR as everytime the page request is sent to the server.
   5. CSR is not useful for the SEO | Websites with the SSR supports the SEO.







