# test-gfm

:smile:

<script src="https://cdn.rawgit.com/knsv/mermaid/7.0.0/dist/mermaid.js" type="text/javascript"></script>

<script>
  var config = {
    startOnLoad: true,
    flowchart: {
      useMaxWidth: false,
      htmlLabels: true
    }
  };
  mermaid.initialize(config);
</script>

<div class="mermaid">
sequenceDiagram
    activate Douglas
    Douglas->>+Tony: Hello Tony, how are you?
    Tony->>+Keith: Hello Keith, how are you?
    Keith-->>-Tony: Great!
    Tony-->>-Douglas: Great!
    Douglas->>+Keith: Hello Keith, how are you?
    Keith-->>-Douglas: Great
    deactivate Douglas
</div>
