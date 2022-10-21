# py-book
Python book blueprint



You can use java version of asciidoctor. Open Windows command prompt as administrator and execute following ([see](https://github.com/asciidoctor/asciidoctorj#windows-installation)):

```powershell
> choco install asciidoctorj
> where asciidoctorj
C:\ProgramData\chocolatey\bin\asciidoctorj.exe
> asciidoctorj -b pdf README.adoc
```



```powershell
> choco install ruby
# You might need to restart the terminal window
> gem install asciidoctor
> gem install pygments.rb
> gem install asciidoctor-diagram
> gem install asciidoctor-pdf --pre
```

Install make:

```powershell
> choco install make
```

Build using make:

```bash
> make html
```

