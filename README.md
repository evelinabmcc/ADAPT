<script>
  window.watsonAssistantChatOptions = {
      integrationID: "453a8e09-81b9-4cfa-91b2-2be252f32eb0", // The ID of this integration.
      region: "us-south", // The region your integration is hosted in.
      serviceInstanceID: "c01f097a-a07f-4ccc-9850-23540c0e7221", // The ID of your service instance.
      onLoad: function(instance) { instance.render(); }
    };
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/loadWatsonAssistantChat.js";
    document.head.appendChild(t);
  });
</script>
