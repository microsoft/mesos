# Mesos at Microsoft

Microsoft and Mesosphere have [partnered][announcement] to bring Mesos to Windows!
Our goal is to help bring [DC/OS to Azure][azure],
with full Mesos support across Azure, on both Linux and Windows.

Our work is all open source, contributed directly upstream to [Apache Mesos][github].
We track our [work log on GitHub][mesos-log], where you can see our progress and current sprint.
All our patches are posted to [Review Board][] through Mesos's [patch submission process][patch].

Users of Mesos on Windows are encouraged to file bugs on [JIRA][],
adding to the [MESOS-3094: Mesos on Windows Epic][epic].
Alternatively, feel free to open issues against this repo to get our immediate attention.
We are also active in the [Mesos Community][community],
where you can find the team members [@andschwa][], [@lilyfang][], [@jeffaco][] and others.

The most up-to-date documentation for building Mesos on Windows can be found [here][windows.md].
We also have unofficial, developer oriented notes available [here][notes].

While it is not yet setup, we are working to provide nightly builds of Mesos on Windows
using a [Jenkins CI system][mesos-jenkins] hosted in Azure.

## [Jenkins Repo][mesos-jenkins]

## [Mesos Repo][github]

## [Microsoft Log / Notes][mesos-log]

## [JIRA Issue Tracker][jira]

## [Review Board][]

[announcement]: https://azure.microsoft.com/en-us/blog/microsoft-and-mesosphere-partner-to-bring-mesos-container-orchestration-across-windows-and-linux-worlds/
[azure]: https://mesosphere.com/azure/

[github]: https://github.com/apache/mesos
[mesos-log]: https://github.com/Microsoft/mesos-log
[review board]: https://reviews.apache.org/dashboard/
[patch]: https://mesos.apache.org/documentation/latest/submitting-a-patch/

[JIRA]: https://issues.apache.org/jira/secure/Dashboard.jspa?selectPageId=12327654
[epic]: https://issues.apache.org/jira/browse/MESOS-3094
[community]: https://mesos.apache.org/community/
[@andschwa]: https://github.com/andschwa/
[@lilyfang]: https://github.com/lilyfang/
[@jeffaco]: https://github.com/jeffaco

[windows.md]: https://github.com/apache/mesos/blob/master/docs/windows.md
[notes]: https://github.com/Microsoft/mesos-log/tree/master/notes

[mesos-jenkins]: https://github.com/Microsoft/mesos-jenkins

### Fine Print

#### Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

#### Legal Notices

Microsoft and any contributors grant you a license to the Microsoft documentation and other content
in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
see the [LICENSE](LICENSE) file, and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation
may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks.
Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all others rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.
