## + Laravle-Bable-Support
Follow the Command
# 1. Install Babel
npm install --save-dev @babel/core @babel/cli\
(or)
npm install @babel/core @babel/cli @babel/preset-env --save-dev

# 2. Install Babel Preset & Class Properties Plugin 
npm install @babel/preset-env --save-dev\
(or)
npm install --save-dev @babel/plugin-proposal-class-properties

# 3. Pest This Code In your package.json File.
"babel": {
        "presets": [
            "@babel/preset-env",
            "@babel/preset-react"
        ],
        "plugins": [
            "@babel/plugin-proposal-class-properties"
        ]
    }
