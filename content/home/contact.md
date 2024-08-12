+++
# Contact widget.
widget = "contact"
active = true
date = 2016-04-20T00:00:00

title = "Contact"
subtitle = ""

# Order that this section will appear in.
weight = 70

# Automatically link email and phone?
autolink = true

# Email form provider
#   0: Disable email form
#   1: Netlify (requires that the site is hosted by Netlify)
#   2: formspree.io
email_form = 2
+++


+++
# Page View Counter
widget = "custom_html"
active = true
date = 2024-08-11T00:00:00

# Order that this section will appear in.
weight = 71

# Custom HTML for displaying the page view counter
[content]
  html = """
  <div id="pageviews" style="font-weight: bold; text-align: center; margin-top: 20px;"></div>
  <script>
    if (typeof(Storage) !== "undefined") {
      let pageViews = localStorage.getItem('pageViews') || 0;
      pageViews++;
      localStorage.setItem('pageViews', pageViews);
      document.getElementById('pageviews').innerText = `Page Views: ${pageViews}`;
    } else {
      document.getElementById('pageviews').innerText = "Page view counter is not supported by your browser.";
    }
  </script>
  """
+++
