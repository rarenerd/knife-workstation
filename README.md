# knife-workstation-cookbook

Installs the basic things you need to do cookbook development on Windows besides Chef DK.

* Atom.io
* Git
* ConEmu

## Supported Platforms

* Windows

## Usage

First grab ChefDK from https://downloads.getchef.com/chef-dk/windows/.

From a git checkout:

```
berks vendor cookbooks
chef-client -z -o knife-workstation
```

## Contributing

1. Fork the repository on Github
2. Create a named feature branch (i.e. `add-new-recipe`)
3. Write you change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request

## License and Authors

Author:: Kristian Vlaardingerbroek (<kvlaardingerbroek@schubergphilis.com>)
