# Getting Started

## Dependencies:
<b>Note</b>: if you've previously installed Gulp globally, run <code>npm rm --global gulp</code> to remove it.

Make sure these are installed first.

<li><a href="https://nodejs.org/en/">Node.js</a></li>
<li><a href="https://gulpjs.com/">Gulp Command Line Utility</a> <code>npm install --global gulp-cli</code></li>

## Quick Start
<ol>
  <li>In bash/terminal/command line, cd into your project directory.</li>
  <li>Run <code>npm install</code> to install required files and dependencies.</li>
  <li>When it's done installing, run one of the task runners to get going:
    <ul>
      <li><code>gulp</code> manually compiles files.</li>
      <li><code>gulp watch</code> automatically compiles files and applies changes using <a href="https://www.browsersync.io/">BrowserSync</a> when you make changes to your source files.</li>
    </ul>
  </li>
</ol>

<b>Try it out.</b> After installing, run <code>gulp</code> to compile some test files into the <code>dist</code> directory. Or, run <code>gulp watch</code> and make some changes to see them recompile automatically.
