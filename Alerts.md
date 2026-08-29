/* Alerts Components */

box-sizing: border-box;

position: relative;
width: 770px;
height: 700px;

background: #F5F5F5;
border: 1px solid rgba(0, 0, 0, 0.4);
border-radius: 2px;


/* _Buttons */

box-sizing: border-box;

position: relative;
width: 270px;
height: 150px;
left: 80px;
top: 478px;

border: 1px dashed #9747FF;
border-radius: 5px;


/* Type=Destructive */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 8px;

position: absolute;
width: 228px;
height: 28px;
left: 20px;
top: 100px;

background: rgba(255, 56, 60, 0.23);
border-radius: 100px;


/* Label */

width: 35px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height, or 123% */
display: flex;
align-items: center;
text-align: center;

color: #FF383C;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Type=Secondary */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 8px;

position: absolute;
width: 228px;
height: 28px;
left: 20px;
top: 60px;

background: #E6E6E6;
mix-blend-mode: plus-darker;
border-radius: 100px;


/* Label */

width: 35px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height, or 123% */
display: flex;
align-items: center;
text-align: center;

color: rgba(0, 0, 0, 0.85);


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Type=Primary */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 8px;

position: absolute;
width: 228px;
height: 28px;
left: 20px;
top: 20px;

background: #0088FF;
border-radius: 100px;


/* Label */

width: 35px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height, or 123% */
display: flex;
align-items: center;
text-align: center;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Alert */

box-sizing: border-box;

position: relative;
width: 590px;
height: 350px;
left: 80px;
top: 80px;

background: #F5F5F5;
border: 1px dashed #6155F5;
border-radius: 5px;


/* Type=Stacked */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: center;
padding: 20px 16px 16px;
gap: 16px;
isolation: isolate;

position: absolute;
width: 260px;
height: 218px;
left: 20px;
top: 20px;

filter: drop-shadow(0px 0px 1px rgba(0, 0, 0, 0.2)) drop-shadow(0px 17px 45px rgba(0, 0, 0, 0.5));
border-radius: 10px;


/* BG - Medium UI */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Fill + Shadow */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, rgba(245, 245, 245, 0.67), rgba(245, 245, 245, 0.67)), #262626;
background-blend-mode: normal, color-dodge;
box-shadow: 0px 8px 40px rgba(0, 0, 0, 0.12);
border-radius: 26px;


/* Glass Effect */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: rgba(0, 0, 0, 0.2);
background-blend-mode: screen;
border-radius: 26px;


/* Icon */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px 6px;
gap: 10px;

display: none;
width: 228px;
height: 64px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* Icon */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 0px;

width: 64px;
height: 64px;

background: url(placeholder-macOS-Default.png);
filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.25));

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Title + Description */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 0px 6px 2px;
gap: 10px;

width: 228px;
height: 70px;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;
z-index: 2;


/* Title */

width: 216px;
height: 16px;

/* Headline/Regular */
font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 16px;
/* identical to box height, or 123% */

color: rgba(0, 0, 0, 0.85);


/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* Description */

width: 216px;
height: 42px;

/* Subheadline/Regular */
font-family: 'SF Pro';
font-style: normal;
font-weight: 400;
font-size: 11px;
line-height: 14px;
/* or 127% */

color: rgba(0, 0, 0, 0.85);


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;


/* Buttons */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 0px;
gap: 6px;

width: 228px;
height: 96px;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;
z-index: 3;


/* Button 1 */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 8px;

width: 228px;
height: 28px;

background: #0088FF;
border-radius: 100px;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* Label */

width: 31px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height, or 123% */
display: flex;
align-items: center;
text-align: center;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Button 2 */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 8px;

width: 228px;
height: 28px;

background: rgba(255, 56, 60, 0.23);
border-radius: 100px;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;


/* Label */

width: 68px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height, or 123% */
display: flex;
align-items: center;
text-align: center;

color: #FF383C;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Button 3 */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 8px;

width: 228px;
height: 28px;

background: #E6E6E6;
mix-blend-mode: plus-darker;
border-radius: 100px;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;


/* Label */

width: 44px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height, or 123% */
display: flex;
align-items: center;
text-align: center;

color: rgba(0, 0, 0, 0.85);


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Type=Side-by-side */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: center;
padding: 20px 16px 16px;
gap: 16px;
isolation: isolate;

position: absolute;
width: 260px;
height: 154px;
left: 310px;
top: 20px;

filter: drop-shadow(0px 0px 1px rgba(0, 0, 0, 0.2)) drop-shadow(0px 17px 45px rgba(0, 0, 0, 0.5));
border-radius: 10px;


/* BG - Medium UI */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Fill + Shadow */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, rgba(245, 245, 245, 0.67), rgba(245, 245, 245, 0.67)), #262626;
background-blend-mode: normal, color-dodge;
box-shadow: 0px 8px 40px rgba(0, 0, 0, 0.12);
border-radius: 26px;


/* Glass Effect */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: rgba(0, 0, 0, 0.2);
background-blend-mode: screen;
border-radius: 26px;


/* Icon */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px 6px;
gap: 10px;

display: none;
width: 228px;
height: 64px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* Icon */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 0px;

width: 64px;
height: 64px;

background: url(placeholder-macOS-Default.png);
filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.25));
border-radius: 0px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Title + Description */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 0px 6px 2px;
gap: 10px;

width: 228px;
height: 70px;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;
z-index: 2;


/* Title */

width: 216px;
height: 16px;

/* Headline/Regular */
font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 16px;
/* identical to box height, or 123% */

color: rgba(0, 0, 0, 0.85);


/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* Description */

width: 216px;
height: 42px;

/* Subheadline/Regular */
font-family: 'SF Pro';
font-style: normal;
font-weight: 400;
font-size: 11px;
line-height: 14px;
/* or 127% */

color: rgba(0, 0, 0, 0.85);


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;


/* Buttons */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 8px;

width: 228px;
height: 32px;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* Secondary */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 8px;

width: 110px;
height: 32px;

background: #E6E6E6;
mix-blend-mode: plus-darker;
border-radius: 100px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 1;


/* Label */

width: 35px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height, or 123% */
display: flex;
align-items: center;
text-align: center;

color: rgba(0, 0, 0, 0.85);


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Primary */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 8px;

width: 110px;
height: 32px;

background: #0088FF;
border-radius: 100px;

/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 1;


/* Label */

width: 35px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height, or 123% */
display: flex;
align-items: center;
text-align: center;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Header */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 0px;
gap: 32px;

position: relative;
width: 1400px;
height: 208px;



/* Component */

width: 1400px;
height: 60px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 56px;
line-height: 60px;
/* identical to box height, or 107% */
display: flex;
align-items: center;
letter-spacing: -0.28px;

color: rgba(0, 0, 0, 0.85);


/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* Description */

width: 1400px;
height: 34px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 400;
font-size: 28px;
line-height: 34px;
/* identical to box height, or 121% */

color: rgba(0, 0, 0, 0.85);


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;


/* Frame */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 8px 0px;
gap: 16px;

width: 1400px;
height: 50px;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;


/* Link */

width: 1400px;
height: 34px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 400;
font-size: 28px;
line-height: 34px;
/* identical to box height, or 121% */
display: flex;
align-items: center;
text-decoration-line: underline;

color: #0088FF;


/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* Link */

display: none;
width: 1400px;
height: 34px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 400;
font-size: 28px;
line-height: 34px;
/* identical to box height, or 121% */
display: flex;
align-items: center;

color: #0088FF;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
