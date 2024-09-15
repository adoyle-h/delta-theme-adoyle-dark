# delta-theme-adoyle-dark

A theme for [delta](https://github.com/dandavison/delta).

Copy below codes to your gitconfig.

```gitconfig
[delta]
    features = adoyle-dark

[delta "adoyle-dark"]
    dark = true
    syntax-theme = Solarized (dark)
    hyperlinks = false
    tabs = 2
    # For diff
    keep-plus-minus-markers = false
    commit-decoration-style = "#ffd21a" ul ol
    commit-style = "#ffd21a" bold
    file-decoration-style = "#1688f0" ol
    file-style = "#1688f0" bold italic
    file-added-label = [A]
    file-copied-label = [C]
    file-modified-label = [M]
    file-removed-label = [D]
    file-renamed-label = [R]
    hunk-header-decoration-style = "#1688f0" box ul
    hunk-header-file-style = "#ABAFB5"
    hunk-header-line-number-style = "#B696DB"
    hunk-header-style = file line-number syntax
    line-numbers = true
    line-numbers-left-format = " {nm:^1} "
    line-numbers-right-format = "{np:^1} "
    line-numbers-zero-style = "#474D53" "#0e0e11"
    line-numbers-left-style = "#474D53" "#0e0e11"
    line-numbers-right-style = "#474D53" "#0e0e11"
    line-numbers-minus-style = "#D01A00" "#0e0e11"
    line-numbers-plus-style = "#18c92d" "#0e0e11"
    minus-emph-style = syntax "#780000"
    minus-style = syntax "#220708"
    plus-emph-style = syntax "#104f10"
    plus-style = syntax "#0a1c07"
    whitespace-error-style = magenta reverse
    zero-style = syntax
    # For blame
    blame-format = "{timestamp:<15} {author:<10} {commit:<8} "
    blame-palette = "#050505" "#151515"
    blame-separator-format = "│{n:^4}"
    # For grep
    grep-file-style = "#1688f0" bold italic ul
    grep-match-line-style = raw
    grep-context-line-style = grey
    grep-match-word-style = red
```


## Copyright and License

Copyright 2024 ADoyle (adoyle.h@gmail.com). Some Rights Reserved.
The project is licensed under the **BSD 3-clause License**.

Read the [LICENSE][] file for the specific language governing permissions and limitations under the License.

Read the [NOTICE][] file distributed with this work for additional information regarding copyright ownership.


<!-- links -->

[LICENSE]: ./LICENSE
[NOTICE]: ./NOTICE
