# How to add css code dynamically using javascript in header
This code can be included in a js file that is included in the `<head>` tag.

    if ($.cookie("takeoverseen") === "1") {
      document.write('<style type="text/css">.takeover-blue.landing{display:none !important}</style>');
    }
