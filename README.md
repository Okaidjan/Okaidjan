⁸- 👋 Hi, I’m @Okaidjan
- 👀 I’m interested in choral music
- 🌱 I’m currently learning systems engineering 
- 💞️ I’m looking to collaborate on networking and programming 
- 📫 How to reach me on okaidjan03@gmail.com or +233540771631 / +233535143597
- 😄 Pronouns: Oklav
- ⚡ Fun fact: simple but difficult to handle
{
  "version": "0.2.0",
  "configurations": [
    {
      "type": "node",
      "request": "launch",
      "name": "Launch Program",
      "skipFiles": ["<node_internals>/**"],
      "program": "${workspaceFolder}\\app.js"
    }
  ]
}
Here's a simple online form using HTML, CSS, and JavaScript for Ampekrom M/A Basic. I'll also provide instructions on how to link your GitHub repository.

*HTML (index.html)*
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ampekrom M/A Basic Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Ampekrom M/A Basic Form</h1>
    </header>
    <main>
        <form id="ampekrom-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Submit</button>
        </form>
    </main>
    <footer>
        <p>View our GitHub repository: <a href="(link unavailable)">Ampekrom M/A Basic</a></p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
```
*CSS (style.css)*
```
- uses: actions/setup-node@v4
  with:
    # Version Spec of the version to use in SemVer notation.
    # It also admits such aliases as lts/*, latest, nightly and canary builds
    # Examples: 12.x, 10.15.1, >=10.15.0, lts/Hydrogen, 16-nightly, latest, node
    node-version: ''

    # File containing the version Spec of the version to use.  Examples: package.json, .nvmrc, .node-version, .tool-versions.
    # If node-version and node-version-file are both provided the action will use version from node-version. 
    node-version-file: ''

    # Set this option if you want the action to check for the latest available version 
    # that satisfies the version spec.
    # It will only get affect for lts Nodejs versions (12.x, >=10.15.0, lts/Hydrogen). 
    # Default: false
    check-latest: false

    # Target architecture for Node to use. Examples: x86, x64. Will use system architecture by default.
    # Default: ''. The action use system architecture by default 
    architecture: ''

    # Used to pull node distributions from https://github.com/actions/node-versions. 
    # Since there's a default, this is typically not supplied by the user. 
    # When running this action on github.com, the default value is sufficient. 
    # When running on GHES, you can pass a personal access token for github.com if you are experiencing rate limiting.
    #
    # We recommend using a service account with the least permissions necessary. Also
    # when generating a new PAT, select the least scopes necessary.
    #
    # [Learn more about creating and using encrypted secrets](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/creating-and-using-encrypted-secrets)
    #
    # Default: ${{ github.server_url == 'https://github.com' && github.token || '' }}
    token: ''

    # Used to specify a package manager for caching in the default directory. Supported values: npm, yarn, pnpm.
    # Package manager should be pre-installed
    # Default: ''
    cache: ''

    # Used to specify the path to a dependency file: package-lock.json, yarn.lock, etc. 
    # It will generate hash from the target file for primary key. It works only If cache is specified.  
    # Supports wildcards or a list of file names for caching multiple dependencies.
    # Default: ''
    cache-dependency-path: ''

    # Optional registry to set up for auth. Will set the registry in a project level .npmrc and .yarnrc file, 
    # and set up auth to read in from env.NODE_AUTH_TOKEN.
    # Default: ''
    registry-url: ''

    # Optional scope for authenticating against scoped registries. 
    # Will fall back to the repository owner when using the GitHub Packages registry (https://npm.pkg.github.com/).
    # Default: ''
    scope: ''

    # Set always-auth option in npmrc file.
    # Default: ''
    always-auth: ''
*JavaScript (script.js)*
```
const form = document.getElementById('ampekrom-form');

form.addEventListener('submit', (e) => {
    e.preventDefault();
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const phone = document.getElementById('phone').value;
    const message = document.getElementById('message').value;

    // Add your form submission logic here
    console.log('Form submitted:', { name, email, phone, message });
});
```

