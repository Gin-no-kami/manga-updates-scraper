## Current Status

This project is a fork of the comic-vine scraper for ComicRack. Functionality will be swapped to support querying the Baka-Updates site for information on Manga series. Currently not working, will update this when the plugin is working.
------------------------------------------------------------------------------------

## Docs and Binaries

All documentation about this project, including the latest downloads and installation instructions
can be found on the Comic Vine Scraper [Wiki page](https://github.com/cbanack/comic-vine-scraper/wiki/).

### Technical Details
 
This project is written for Windows, using IronPython and the .NET library.  It displays WinForms graphics and makes heavy use of the [ComicVine RESTful API](http://www.comicvine.gamespot.com/api/).  It is a _plugin_ for the [ComicRack](http://comicrack.cyolito.com/) comic book reader, which is a standalone Windows desktop application.  Except during development (see below), Comic Vine Scraper does _not_ run outside of ComicRack's plugin environment.   

This project is currently set up to compile and run in the [VS Code](https://code.visualstudio.com/) IDE using the [Microsoft Python Extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) with properly installed versions of both Python (for parsing source code in the IDE) and IronPython (for running the code using .NET assemblies).  In other words, you should have _ipy.exe_, _python.exe_, and _pylint.exe_ working on your command-line before you get started.

You should also get Java and Ant (i.e. _java.exe_ and _ant.exe_) installed and running, since this project uses Ant to build, test, and run the plugin during development.

All code is written for Python version 2, not 3.

### Pull Requests

At this point, I am not accepting pull requests.  Comic Vine Scraper is a stable, mature project and most of the work on it these days is maintenance and bug fixing.  I may accept well-written pull requests for straightforward bug fixes, but _please contact me_ before you start doing any significant work.  I don't want to waste your time.

### License 

This project is created and distributed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).
This is an open source license, so you are welcome to create, build, and maintain your own fork of the codebase if you have a major enhancement that you want to add, or a wild new direction that you'd like to take the project.

    Unless required by applicable law or agreed to in writing, software 
    distributed under this License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
