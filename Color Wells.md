/* Color Wells */

box-sizing: border-box;

position: relative;
width: 170px;
height: 210px;

background: #F5F5F5;
border: 1px solid rgba(0, 0, 0, 0.4);
border-radius: 2px;


/* Color Well */

box-sizing: border-box;

position: relative;
width: 68px;
height: 110px;
left: 50px;
top: 50px;

border: 1px dashed #9747FF;
border-radius: 5px;


/* Color Selected=False */

position: absolute;
width: 28px;
height: 28px;
left: 20px;
top: 60px;

border-radius: 100px;


/* Button */

box-sizing: border-box;

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

border-radius: 100px;


/* Color */

position: absolute;
left: 5px;
right: 5px;
top: 5px;
bottom: 5px;

background: #FF0000;
border-radius: 100px;


/* Color Selected=True */

position: absolute;
width: 28px;
height: 28px;
left: 20px;
top: 20px;

background: radial-gradient(50% 50% at 50% 50%, #FFFFFF 4%, rgba(255, 255, 255, 0.66) 41.35%, rgba(255, 255, 255, 0.330806) 73.56%, rgba(255, 255, 255, 0) 96%), conic-gradient(from 180deg at 50% 50%, #FF0000 0deg, #FB00FF 72deg, #00A1FF 144deg, #44FF00 216deg, #FFF700 288deg, #FF0000 360deg);
border-radius: 100px;


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
