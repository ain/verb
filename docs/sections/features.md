- Generate markdown docs, or HTML
- Generate a Table of Contents simply by adding `<!!-- toc -->` to any document.
- Include templates from locally installed npm packages with the `{%%= include() %}` helper
- Include templates from your project's `docs/` directory with the `{%%= docs() %}` helper
- Change the templates directory for either helper by passing a `cwd` to the helper: example: `{%%= docs("foo", {cwd: ''}) %}`
