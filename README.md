# AI Code Generator

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Anibalduarte-web/Interceptor10.git
   cd Interceptor10
   ```

2. **Install dependencies**:
   ```bash
   npm install  # or yarn install
   ```

3. **Build the project**:
   ```bash
   npm run build  # or yarn build
   ```

4. **Run the application**:
   ```bash
   npm start  # or yarn start
   ```

## Examples

### Example 1: Generate Code
```javascript
const generator = new AICodeGenerator();
const code = generator.generate('function add(a, b) { return a + b; }');
console.log(code);
```

### Example 2: Customize Output
```javascript
const options = { style: 'clean', comments: true };
const code = generator.generate('function subtract(a, b) { return a - b; }', options);
console.log(code);
```