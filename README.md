# Eclipse Solargraph 
<a href="https://marketplace.eclipse.org/content/ruby-solargraph">
<img src ="https://img.shields.io/eclipse-marketplace/v/ruby-solargraph.svg" />
</a>
<a href="https://marketplace.eclipse.org/content/ruby-solargraph">
<img src ="https://img.shields.io/eclipse-marketplace/favorites/ruby-solargraph.svg" />
</a>
<a href="https://marketplace.eclipse.org/content/ruby-solargraph">
<img src ="https://img.shields.io/eclipse-marketplace/dt/ruby-solargraph.svg" />
</a>

**Ruby development tools combining the powers of the Eclipse IDE and the Solargraph language server!**

<p align="center" style="font-size:6px;">
<img src ="https://github.com/PyvesB/eclipse-solargraph/blob/master/images/editor.png?raw=true" width="32%" />
<img src ="https://github.com/PyvesB/eclipse-solargraph/blob/master/images/bundle-install.png?raw=true" width="32%" />
<img src ="https://github.com/PyvesB/eclipse-solargraph/blob/master/images/debugger.png?raw=true" width="32%" />
<br />
<i><sub>Left: syntax highlighting, completions, docs, code outline, references, diagnostics and more! Middle: bundle install on Gemfile. Right: debugger with interactive console.</sub></i>
</p>

## :gem: Features at a glance

* Rich syntax highlighting and code folding
* Code completion
* Documentation hovers
* Rename refactoring
* Find references and mark occurrences
* Jump to declarations
* Code outline
* Compiler warnings based on Rubocop rules
* Code formatter
* Interactive debugger
* Run Ruby scripts with customisable launch configurations
* Run `bundle install` on Gemfiles and `gem build` on gemspec files
* Support for web development with ERB Rails files
* Various other features part of the Language Server Protocol

Check out what's new in the [latest releases](https://github.com/PyvesB/eclipse-solargraph/releases)!

## :cd: Plugin installation

You can install the plugin via **[the Eclipse Marketplace](https://marketplace.eclipse.org/content/ruby-solargraph/)**, or simply drag the following button to your running Eclipse window:

<p align="center">
<a href="http://marketplace.eclipse.org/marketplace-client-intro?mpc_install=4611382" class="drag" title="Drag to your running Eclipse* workspace. *Requires Eclipse Marketplace Client"><img style="width:80px;" typeof="foaf:Image" class="img-responsive" src="https://marketplace.eclipse.org/sites/all/themes/solstice/public/images/marketplace/btn-install.svg" alt="Drag to your running Eclipse* workspace. *Requires Eclipse Marketplace Client" /></a>
</p>

Alternatively, head to the [update site](https://pyvesb.github.io/eclipse-solargraph/) and follow the instructions listed there.

Once installed, the plugin will simply kick in when opening any Ruby file in Eclipse; there is no Ruby-specific project type or perspective.

## :date: Compatibility

This plugin requires Java 11 or more recent.

The aim is to provide support for all Eclipse releases that are at **up to two years old**. Versions older than that may be dropped at any point without notice. That being said, the plugin should currently still work with Eclipse versions as old as **2019-03** (4.11).

## :sparkles: Tips and tricks

* You can fine-tune Solargraph's behaviour by [creating a .solargraph.yml configuration file](https://solargraph.org/guides/configuration).
* Similarly, you can fine-tune the code formatting and compiler warnings with a .rubocop.yml file.
* To improve code completion and intellisense, it is recommended to generate YARD documentation for your gems (run `yard gems` in a terminal).
* For web development on ERB files, it is recommended to also install the [Wild Web Developer](https://github.com/eclipse/wildwebdeveloper) plugin.

## :star: Support and feedback

Found a problem or need some help? Simply open an [**issue**](https://github.com/PyvesB/eclipse-solargraph/issues)!

Find the project useful or interesting? **Star** the repository by clicking on the icon on the top right of this page!

## :computer: Code contributions

Want to make this plugin better, faster, stronger? Contributions are more than welcome, open a **pull request** and share your code!

Setting up your own working copy of the project is easy:
* Download the [RCP and RAP Developers](https://eclipse.org/downloads/eclipse-packages/) version of Eclipse.
* Fork the repository by clicking on the *Fork* icon on the top right of this page and clone it locally.
* In Eclipse, go to `File` -> `Import...` -> `General` -> `Existing Projects into Workspace`.
* In the `Select root directory` field, indicate the location where you checked out the eclipse-solargraph repository.
* Ensure `Search for nested projects` is enabled, select all projects in the `Projects` field and click `Finish`.
* Open `eclipse-solargraph-target-platform.target` and click `Set as Active Target Platform`.
* You're ready to go! You can now either launch an Eclipse instance by right-clicking on the plugin project and selecting `Run As` -> `Eclipse Application`, or you can export a plugin archive file by selecting `Export` -> `Deployable plug-ins and fragments`.

## :balance_scale: License and acknowledgements

Eclipse Solargraph licensed under Eclipse Public License - v 2.0.

The following projects are used by this plugin:
* [Solargraph](http://solargraph.org/) by [castwide](https://github.com/castwide): underlying language server (MIT License) and adapted marketplace logo (CC BY-SA License).
* [Readapt](https://github.com/castwide/readapt) by [castwide](https://github.com/castwide): debugger (MIT License).
* [LSP4E](https://github.com/eclipse/lsp4e): Language Server Protocol support in the Eclipse IDE (Eclipse Public License).
* [TextMate](https://github.com/textmate): Ruby language grammars (MIT License).
* [Ruby](https://www.ruby-lang.org): launch shortcut logo (Creative Commons License).
