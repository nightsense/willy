<h1 id="willy">willy</h1>

<p>A vim theme inspired by the <a href="http://zambumon.github.io/">Amazing Chocolatier keycap set</a> by Zambumon.</p>

<h2 id="screenshots">screenshots</h2>

<table>
<tr></tr><tr><td align="center"><strong>willy-<br />light</strong></td>
<td align="center"><img src="/img/screenshot-willy-light.png" alt="screenshot of the willy-light vim theme" width="288" /> <img src="/img/screenshot-willy-dark.png" alt="screenshot of the willy-dark vim theme" width="288" /></td>
<td align="center"><strong>willy-<br />dark</strong></td></tr>
</table>

<h2 id="setup">setup</h2>

<h3 id="installation">installation</h3>

<p>While vim themes can be installed manually (place <a href="https://github.com/nightsense/willy/tree/master/colors">theme file</a> in <code class="highlighter-rouge">~/.vim/colors/</code>), a <strong>plugin helper</strong> is recommended.</p>

<p>If you don’t have a preferred helper, consider trying <a href="https://github.com/junegunn/vim-plug">vim-plug</a>, which can be installed with:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
</code></pre>
</div>

<p>To install willy via vim-plug, add the following to the top of your <code class="highlighter-rouge">vimrc</code>:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>call plug#begin('~/.vim/plugged')
Plug 'nightsense/willy'
call plug#end()
</code></pre>
</div>

<p>Then restart vim and run <code class="highlighter-rouge">PlugUpdate</code> (from the vim command line).</p>

<h3 id="activation">activation</h3>

<p>To activate the willy theme, add one of the following lines to your <code class="highlighter-rouge">vimrc</code>:</p>

<ul>
  <li><code class="highlighter-rouge">colorscheme willy-light</code></li>
  <li><code class="highlighter-rouge">colorscheme willy-dark</code></li>
</ul>

<p>Note that the <code class="highlighter-rouge">background</code> setting doesn’t affect this theme.</p>

<blockquote>
  <p>To assign themes to specific intervals of the day, try the <a href="https://github.com/nightsense/night-and-day">night-and-day</a> plugin.</p>
</blockquote>

<h2 id="terminal-vim">terminal vim</h2>

<p>See the <a href="https://github.com/nightsense/nightshell">nightshell</a> repository, which allows willy to be used in a variety of terminal applications.</p>

<h2 id="palette">palette</h2>

<p>willy consists of 16 colours:</p>

<ul>
  <li>8 theme-distinct <strong>base colours</strong>, which meet the <a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html#visual-audio-contrast-contrast-73-head">3:1 ISO standard</a> for text/background contrast ratio</li>
  <li>8 standard <strong>accent colours</strong> (shared by members of the “nightsense theme family”), for syntax highlighting
    <ul>
      <li>hue selection at the scale of 1/12 (30°) colour wheel intervals, followed by 1/12 subinterval adjustments</li>
      <li>value and saturation tuned for light backgrounds, then saturation lowered for dark backgrounds</li>
      <li>again, ISO contrast ratio was observed</li>
    </ul>
  </li>
</ul>

<table>
  <thead>
    <tr>
      <th style="text-align: right">base</th>
      <th style="text-align: center">light-background accents</th>
      <th style="text-align: left">dark-background accents</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/2b1607.png" height="24" width="42" /> <code class="highlighter-rouge">2b1607</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/eb403a.png" height="24" width="42" /> <code class="highlighter-rouge">eb403a</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/eb6663.png" height="24" width="42" /> <code class="highlighter-rouge">eb6663</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/40210b.png" height="24" width="42" /> <code class="highlighter-rouge">40210b</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/eb6d13.png" height="24" width="42" /> <code class="highlighter-rouge">eb6d13</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/eb8f4e.png" height="24" width="42" /> <code class="highlighter-rouge">eb8f4e</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/542f15.png" height="24" width="42" /> <code class="highlighter-rouge">542f15</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/ebce3b.png" height="24" width="42" /> <code class="highlighter-rouge">ebce3b</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/ebd463.png" height="24" width="42" /> <code class="highlighter-rouge">ebd463</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/754727.png" height="24" width="42" /> <code class="highlighter-rouge">754727</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/259433.png" height="24" width="42" /> <code class="highlighter-rouge">259433</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/63946a.png" height="24" width="42" /> <code class="highlighter-rouge">63946a</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/94623e.png" height="24" width="42" /> <code class="highlighter-rouge">94623e</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/009488.png" height="24" width="42" /> <code class="highlighter-rouge">009488</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/56948f.png" height="24" width="42" /> <code class="highlighter-rouge">56948f</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/bf906f.png" height="24" width="42" /> <code class="highlighter-rouge">bf906f</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/308bbf.png" height="24" width="42" /> <code class="highlighter-rouge">308bbf</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/609cbf.png" height="24" width="42" /> <code class="highlighter-rouge">609cbf</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/e0b596.png" height="24" width="42" /> <code class="highlighter-rouge">e0b596</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/8c60bf.png" height="24" width="42" /> <code class="highlighter-rouge">8c60bf</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/9e80bf.png" height="24" width="42" /> <code class="highlighter-rouge">9e80bf</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/ffe6d4.png" height="24" width="42" /> <code class="highlighter-rouge">ffe6d4</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/e05e8e.png" height="24" width="42" /> <code class="highlighter-rouge">e05e8e</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/e082a4.png" height="24" width="42" /> <code class="highlighter-rouge">e082a4</code></td>
    </tr>
  </tbody>
</table>

<p><img src="http://www.colorhexa.com/eb6663.png" height="24" width="42" />
<strong>Red</strong>, the colour of alarm, is used for <strong>warning elements</strong>, including error messages, misspellings, and diff deletions.</p>

<p><img src="http://www.colorhexa.com/eb8f4e.png" height="24" width="42" />
<strong>Orange</strong> is the colour of fire, which serves as a preliminary to many practical activities. Orange is therefore used for <strong>preliminary elements</strong>, such as preprocessor commands (which prepare data to be handled by another program), incremental searching (that is, a search term in the process of being typed), titles, and miscapitalized words.</p>

<p><img src="http://www.colorhexa.com/ebd463.png" height="24" width="42" />
<strong>Yellow</strong>, the classic highlighting colour, is applied to elements that are not warnings yet should draw attention with high visibility. These <strong>highlighted elements</strong> include search results, task tags (<code class="highlighter-rouge">TODO</code>, <code class="highlighter-rouge">FIXME</code>…), and diff changes.</p>

<p><img src="http://www.colorhexa.com/63946a.png" height="24" width="42" />
<strong>Green</strong>, the colour that says “go ahead, proceed with the task at hand”, is used for positive <strong>action elements</strong>, such as statements (if/then, while/do, case…), mode indicators (insert, visual…), vim user prompts, and diff additions.</p>

<p><img src="http://www.colorhexa.com/56948f.png" height="24" width="42" />
<strong>Teal</strong> is named after the “common teal”, a kind of duck, thus connecting this colour with the concept of “species”, which is a means of classifying life into very specific types. Teal is therefore used for specifying <strong>object types</strong>, such as data type (boolean, integer, string…) or storage class (static, volatile…), as well as mislocalized words (that is, words that are not misspelled but of the wrong type, namely a foreign type).</p>

<p><img src="http://www.colorhexa.com/609cbf.png" height="24" width="42" />
<strong>Blue</strong>, a colour of calm stability, is used for <strong>constants</strong>, which come in the form of boolean values, integers, floating-point numbers, characters, and strings.</p>

<p><img src="http://www.colorhexa.com/9e80bf.png" height="24" width="42" />
<strong>Purple</strong>, often associated with rare purple dyes historically produced for special works of art, is used for <strong>special text</strong>, including special characters (standalone or within syntax units), vim tags, and debugging statements. Rarely-used words are also marked, allowing the writer to consider whether such a specially uncommon word is appropriate.</p>

<p><img src="http://www.colorhexa.com/e082a4.png" height="24" width="42" />
<strong>Pink</strong>, the colour of spring blossoms, is used for <strong>object names</strong>, including the names of variables and functions. To code is to bring countless objects blossoming into existence as one types their names.</p>
