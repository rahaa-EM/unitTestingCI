# react-test-example - starter code 

# Steps:
1. Create a GitHub repo with this starter code
2. Clone the repo to your local computer
3. npm install
4. create .env and add your own MongoDB Atlas connection string, then use the environment variable on connection.js
5. Create a new branch 'unittest'
6. write App.test.js
the most simple example
```
    import { render, screen } from '@testing-library/react';
    import App from './App';
    import '@testing-library/jest-dom';
    
    test('renders GetToDoItem component', () => {
	render(<App />);
	const linkElement = screen.getByText('My To Do Items');
	expect(linkElement).toBeInTheDocument();
    });
 ```
7. run npm test
8. commit and push
