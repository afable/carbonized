<h1 id="carbonized">carbonized</h1>

<p>A vim theme inspired by the <a href="https://geekhack.org/index.php?topic=79693.0">Carbon keycap set</a> by T0mb3ry.</p>

<h2 id="screenshots">screenshots</h2>

<table>
<tr></tr><tr><td align="center"><strong>carbonized-<br />light</strong></td>
<td align="center"><img src="/img/screenshot-carbonized-light.png" alt="screenshot of the carbonized-light vim theme" width="288" /> <img src="/img/screenshot-carbonized-dark.png" alt="screenshot of the carbonized-dark vim theme" width="288" /></td>
<td align="center"><strong>carbonized-<br />dark</strong></td></tr>
</table>

<h2 id="setup">setup</h2>

<h3 id="installation">installation</h3>

<p>While you can install a theme manually (by placing a <a href="https://github.com/nightsense/carbonized/tree/master/colors">theme file</a> in <code class="highlighter-rouge">~/.vim/colors/</code>), a <strong>plugin helper</strong> is recommended.</p>

<p>If you don’t have a preferred helper, consider trying <a href="https://github.com/junegunn/vim-plug">vim-plug</a>, which can be installed with:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
</code></pre>
</div>

<p>To install carbonized via vim-plug, add the following to the top of your <code class="highlighter-rouge">vimrc</code>:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>call plug#begin('~/.vim/plugged')
Plug 'nightsense/carbonized'
call plug#end()
</code></pre>
</div>

<p>Then restart vim and run <code class="highlighter-rouge">PlugUpdate</code> (from the vim command line).</p>

<h3 id="activation">activation</h3>

<p>To activate the carbonized theme, add one of the following lines to your <code class="highlighter-rouge">vimrc</code>:</p>

<ul>
  <li><code class="highlighter-rouge">colorscheme carbonized-light</code></li>
  <li><code class="highlighter-rouge">colorscheme carbonized-dark</code></li>
</ul>

<p>Note that the <code class="highlighter-rouge">background</code> setting doesn’t affect this theme.</p>

<blockquote>
  <p>To assign themes to specific intervals of the day, try the <a href="https://github.com/nightsense/night-and-day">night-and-day</a> plugin.</p>
</blockquote>

<h2 id="terminal-vim">terminal vim</h2>

<p>To make this theme work in terminal vim, install <a href="https://github.com/nightsense/nightshell">nightshell</a> to <code class="highlighter-rouge">~/.nightshell</code>:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>git clone https://github.com/nightsense/nightshell ~/.nightshell
</code></pre>
</div>

<h2 id="colours">colours</h2>

<h3 id="carbonized-palette">carbonized palette</h3>

<table>
  <thead>
    <tr>
      <th style="text-align: right">hex</th>
      <th style="text-align: center">base</th>
      <th style="text-align: center">accent</th>
      <th style="text-align: left">hex</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">1f1f1f</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/1f1f1f.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/bf5062.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">bf5062</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">303030</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/303030.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/d47546.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">d47546</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">524f4b</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/524f4b.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/ab982b.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">ab982b</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">706d67</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/706d67.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/609456.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">609456</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">99958d</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/99958d.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/3e9486.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">3e9486</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">bfbab0</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/bfbab0.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/6393ab.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">6393ab</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">e8e2d5</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/e8e2d5.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/8572ab.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">8572ab</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">fff8eb</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/fff8eb.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/ab7298.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">ab7298</code></td>
    </tr>
  </tbody>
</table>

<h3 id="syntax-highlighting-logic">syntax highlighting logic</h3>

<p><img src="http://www.colorhexa.com/bf5062.png" height="24" width="42" /> <strong>Red</strong>, the colour of alarm, is used for <strong>critical messages</strong> like errors, warnings, misspellings, and diff deletions.</p>

<table>
  <thead>
    <tr>
      <th style="text-align: left">colour</th>
      <th style="text-align: left">role</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left"> </td>
      <td style="text-align: left">the colour of <strong>alerts</strong>, providing critical information<br /></td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><img src="http://www.colorhexa.com/d47546.png" height="24" width="42" /> </td>
      <td><strong>orange flames</strong> of fire, which often serves as a preliminary to other activities</td>
      <td><strong>preliminary elements</strong>: preprocessor commands (which modify data for handling by another program), incremental search (the highlighting of the search term as one types it in, before striking enter to complete it), titles (which precede content), vim question prompts (which precede user-supplied answers), miscapitalized words</td>
    </tr>
    <tr>
      <td><img src="http://www.colorhexa.com/ab982b.png" height="24" width="42" /> </td>
      <td><strong>yellow highlighting</strong> that draws attention to important information</td>
      <td><strong>highlighting</strong> of routine information: search results, task tags (TODO, FIXME, BUG…), diff changes</td>
    </tr>
    <tr>
      <td><img src="http://www.colorhexa.com/609456.png" height="24" width="42" /> </td>
      <td><strong>green lights/objects</strong> that say “go ahead, proceed with the task at hand”</td>
      <td><strong>action elements</strong>: statements (if/then, while/do, case…), mode indicator (insert, visual…), “press enter to continue” prompt, diff additions</td>
    </tr>
    <tr>
      <td><img src="http://www.colorhexa.com/3e9486.png" height="24" width="42" /> </td>
      <td>the <strong>common teal</strong>, a very specific type of duck</td>
      <td><strong>object types</strong>, such as data type (boolean, integer, string…) or storage class (static, volatile…); also, words that are spelled properly but mislocalized (that is, of a foreign type)</td>
    </tr>
    <tr>
      <td><img src="http://www.colorhexa.com/6393ab.png" height="24" width="42" /> </td>
      <td><strong>sea and sky</strong>: enduring, seemingly unchanging constants of the world</td>
      <td><strong>constants</strong>: bits of static, concrete information, whether boolean values, integers, floating-point numbers, characters, strings…</td>
    </tr>
    <tr>
      <td><img src="http://www.colorhexa.com/8572ab.png" height="24" width="42" /> </td>
      <td><strong>purple dye</strong>, historically a rare luxury, reserved for special works of art</td>
      <td><strong>special text</strong>: special characters (standalone or within syntax units), vim tags, debugging statements, rarely-used words</td>
    </tr>
    <tr>
      <td><img src="http://www.colorhexa.com/ab7298.png" height="24" width="42" /> </td>
      <td><strong>pink blossoms</strong> of springtime, each one a fresh, brand new burst of life</td>
      <td><strong>object names</strong>: names of objects, including variables and functions (by naming objects, they too burst into life)</td>
    </tr>
  </tbody>
</table>
