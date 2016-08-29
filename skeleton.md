What happens to the layout when you resize the screen to less than 550 px. How do you think that works?

  The layout changes at screens less than 550px wide. When you resize the browser, getting smaller the columns get smaller, until 550px is reached and the layout changes to a one column layout. This is done to make the site easily readable from a mobile device.

  This is most probably done via a media query that would look something like @media screen( max width: 550px){*change to one column*}.
  It is also done with the use of relative units for font-sizes (rems) and margins, borders and paddings (%).
