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

<p>While themes can be installed manually (by placing a <a href="https://github.com/nightsense/willy/tree/master/colors">theme file</a> in <code class="highlighter-rouge">~/.vim/colors/</code>), a <strong>plugin helper</strong> is recommended.</p>

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

<h2 id="design">design</h2>

<h3 id="palette">palette</h3>

<p>willy features:</p>

<ul>
  <li>8 theme-distinct <strong>base colours</strong>, used for most text (normal text, comments, line numbers…)  and visual elements, and meeting the <a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html#visual-audio-contrast-contrast-73-head">3:1 ISO text/background contrast ratio standard</a> for</li>
  <li>a hand-tuned selection of 8 <strong>accent colours</strong>, common to the nightsense theme family, for syntax highlighting
    <ul>
      <li>hue selection was made at the coarse scale of 1/12 (30°) colour wheel intervals, followed by adjustment on a fine scale of 1/12 subintervals</li>
      <li>value and saturation were manually tuned for light backgrounds, then saturation was lowered for dark backgrounds</li>
      <li>again, ISO contrast ratio was observed</li>
    </ul>
  </li>
</ul>

<table>
  <thead>
    <tr>
      <th style="text-align: right">base colours</th>
      <th style="text-align: center">light-background accents</th>
      <th style="text-align: left">dark-background accents</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/1f130d.png" height="24" width="42" /> <code class="highlighter-rouge">1f130d</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/.png" height="24" width="42" /> `` </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/ff5a54.png" height="24" width="42" /> <code class="highlighter-rouge">ff5a54</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/302018.png" height="24" width="42" /> <code class="highlighter-rouge">302018</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/.png" height="24" width="42" /> `` </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/eb8f4e.png" height="24" width="42" /> <code class="highlighter-rouge">eb8f4e</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/523a29.png" height="24" width="42" /> <code class="highlighter-rouge">523a29</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/.png" height="24" width="42" /> `` </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/ebd43b.png" height="24" width="42" /> <code class="highlighter-rouge">ebd43b</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/705441.png" height="24" width="42" /> <code class="highlighter-rouge">705441</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/.png" height="24" width="42" /> `` </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/5c9e65.png" height="24" width="42" /> <code class="highlighter-rouge">5c9e65</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/997959.png" height="24" width="42" /> <code class="highlighter-rouge">997959</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/.png" height="24" width="42" /> `` </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/5c9e99.png" height="24" width="42" /> <code class="highlighter-rouge">5c9e99</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/bfa580.png" height="24" width="42" /> <code class="highlighter-rouge">bfa580</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/.png" height="24" width="42" /> `` </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/75aac9.png" height="24" width="42" /> <code class="highlighter-rouge">75aac9</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/e8d0ae.png" height="24" width="42" /> <code class="highlighter-rouge">e8d0ae</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/.png" height="24" width="42" /> `` </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/a687c9.png" height="24" width="42" /> <code class="highlighter-rouge">a687c9</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/fff2e0.png" height="24" width="42" /> <code class="highlighter-rouge">fff2e0</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/.png" height="24" width="42" /> `` </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/e082a9.png" height="24" width="42" /> <code class="highlighter-rouge">e082a9</code></td>
    </tr>
  </tbody>
</table>

<h3 id="syntax-highlighting-logic">syntax highlighting logic</h3>

<p><img src="http://www.colorhexa.com/.png" height="24" width="42" />
<strong>Red</strong>, the colour of alarm, is used for <strong>warning elements</strong>, including error messages, misspellings, and diff deletions.</p>

<p><img src="http://www.colorhexa.com/.png" height="24" width="42" />
<strong>Orange</strong> is the colour of fire, which serves as a preliminary to many practical activities. Orange is therefore used for <strong>preliminary elements</strong>, such as preprocessor commands (which prepare data to be handled by another program), incremental searching (that is, a search term in the process of being typed), titles, and miscapitalized words.</p>

<p><img src="http://www.colorhexa.com/.png" height="24" width="42" />
<strong>Yellow</strong>, the classic highlighting colour, is applied to elements that are not warnings yet should draw attention with high visibility. These <strong>highlighted elements</strong> include search results, task tags (<code class="highlighter-rouge">TODO</code>, <code class="highlighter-rouge">FIXME</code>…), and diff changes.</p>

<p><img src="http://www.colorhexa.com/.png" height="24" width="42" />
<strong>Green</strong>, the colour that says “go ahead, proceed with the task at hand”, is used for positive <strong>action elements</strong>, such as statements (if/then, while/do, case…), mode indicators (insert, visual…), vim user prompts, and diff additions.</p>

<p><img src="http://www.colorhexa.com/.png" height="24" width="42" />
<strong>Teal</strong> is named after the “common teal”, a kind of duck, thus connecting this colour with the concept of “species”, which is a means of classifying life into very specific types. Teal is therefore used for specifying <strong>object types</strong>, such as data type (boolean, integer, string…) or storage class (static, volatile…), as well as mislocalized words (that is, words that are not misspelled but of the wrong type, namely a foreign type).</p>

<p><img src="http://www.colorhexa.com/.png" height="24" width="42" />
<strong>Blue</strong>, a colour of calm stability, is used for <strong>constants</strong>, which come in the form of boolean values, integers, floating-point numbers, characters, and strings.</p>

<p><img src="http://www.colorhexa.com/.png" height="24" width="42" />
<strong>Purple</strong>, often associated with rare purple dyes historically produced for special works of art, is used for <strong>special text</strong>, including special characters (standalone or within syntax units), vim tags, and debugging statements. Rarely-used words are also marked, allowing the writer to consider whether such a specially uncommon word is appropriate.</p>

<p><img src="http://www.colorhexa.com/.png" height="24" width="42" />
<strong>Pink</strong>, the colour of spring blossoms, is used for <strong>object names</strong>, including the names of variables and functions. To code is to bring countless objects blossoming into existence as one types their names.</p>
