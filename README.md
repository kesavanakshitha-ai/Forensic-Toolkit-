import React from 'react';

const BallisticsIcon: React.FC<React.SVGProps<SVGSVGElement>> = (props) => (
  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth={1.5} stroke="currentColor" {...props}>
    <path strokeLinecap="round" strokeLinejoin="round" d="M12.75 3.75v16.5M7.5 12.75h9M19.5 12.75l-7.5 7.5-7.5-7.5" />
    <path strokeLinecap="round" strokeLinejoin="round" d="M3.75 6.75c0-1.104.896-2 2-2h12.5c1.104 0 2 .896 2 2v10.5c0 1.104-.896 2-2 2H5.75c-1.104 0-2-.896-2-2V6.75z" />
    <path strokeLinecap="round" strokeLinejoin="round" d="M15.75 6.75L12 10.5l-3.75-3.75" />
  </svg>
);

export default BallisticsIcon;
import React from 'react';

const BloodstainIcon: React.FC<React.SVGProps<SVGSVGElement>> = (props) => (
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" {...props}>
    {/* Darker core */}
    <path fill="#991B1B" d="M13.2 10.3c-.6.3-1 .9-1 1.6-.1.7.2 1.4.7 1.9.5.5 1.2.8 1.9.7.7-.1 1.3-.5 1.6-1.1.2-.3.3-.7.3-1s-.1-.7-.3-1c-.3-.6-.8-1-1.4-1.2-1.1-.3-2.3 0-3.1.2z"/>

    {/* Main splatter */}
    <g fill="#DC2626">
      <path d="M12.1 6.6c-1 .04-2.1.3-2.9 1.2-.9 1-1.3 2.3-1.1 3.7.3 1.9 1.6 3.5 3.3 4.4 1.7.9 3.6.9 5.3.1 1.7-.8 2.8-2.5 2.8-4.4 0-1.9-1-3.7-2.7-4.7-1.1-.6-2.4-.8-3.7-.7z"/>
      <path d="M11.6 6.7l-.4-2.1-.2 2.1z M16.7 8.3l1.8-1.2.1 2.2z M17.9 11.4l2.4.1-1.9.9z M16.4 14.5l1.5 1.5-1.1-1.9z M12.5 16.3l-.2 2.4-1.3-1.6z M8.1 14.2l-1.7 1.2.8-2.1z M7 10.9l-2.4-.4 2-.8z M8.5 7.8L7 6.6l1.7 1z"/>
      <path d="M14.3 15.5c.2.6.3 1.2.2 1.8-.1.7-.4 1.3-.8 1.8-.3.3-.7.5-1.1.6h-.2c-.5-.1-.9-.4-1.2-.8-.5-.6-.8-1.4-.7-2.2.1-.8.5-1.5 1.1-2.1.2-.2.5-.4.8-.4s.6.1.8.3z"/>
      <path d="M12.9 20.1c0 .5-.2 1-.5 1.4-.3.4-.7.6-1.1.6s-.8-.2-1.1-.6-.5-.9-.5-1.4c0-.6.2-1.1.6-1.5.2-.2.5-.3.8-.3s.6.1.8.3c.4.4.6.9.6 1.5z"/>
    </g>

    {/* Darker specks */}
    <g fill="#B91C1C">
      <circle cx="17.2" cy="5.2" r="0.5"/>
      <circle cx="18.9" cy="6.8" r="0.7"/>
      <circle cx="20.5" cy="9.5" r="0.6"/>
      <circle cx="19.8" cy="14.8" r="0.8"/>
      <circle cx="16.5" cy="17.5" r="0.5"/>
      <circle cx="11.2" cy="19.2" r="0.4"/>
      <circle cx="6.8" cy="16.9" r="0.6"/>
      <circle cx="5.1" cy="13.2" r="0.7"/>
      <circle cx="4.5" cy="8.1" r="0.5"/>
      <circle cx="7.2" cy="4.9" r="0.8"/>
      <circle cx="10.5" cy="4.1" r="0.6"/>
      <circle cx="14.2" cy="4.3" r="0.4"/>
      <circle cx="5.5" cy="5.1" r="0.3"/>
      <circle cx="19" cy="11" r="0.3"/>
    </g>
  </svg>
);

export default BloodstainIcon;
import React from 'react';

const CameraIcon: React.FC<React.SVGProps<SVGSVGElement>> = (props) => (
  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth={1.5} stroke="currentColor" {...props}>
    <path strokeLinecap="round" strokeLinejoin="round" d="M6.827 6.175A2.31 2.31 0 015.186 7.23c-.38.054-.757.112-1.134.175C2.999 7.58 2.25 8.507 2.25 9.574V18a2.25 2.25 0 002.25 2.25h15A2.25 2.25 0 0021.75 18V9.574c0-1.067-.75-1.994-1.802-2.169a47.865 47.865 0 00-1.134-.175 2.31 2.31 0 01-1.64-1.055l-.822-1.316a2.192 2.192 0 00-1.736-1.039 48.776 48.776 0 00-5.232 0 2.192 2.192 0 00-1.736 1.039l-.821 1.316z" />
    <path strokeLinecap="round" strokeLinejoin="round" d="M16.5 12.75a4.5 4.5 0 11-9 0 4.5 4.5 0 019 0zM18.75 10.5h.008v.008h-.008V10.5z" />
  </svg>
);

export default CameraIcon;
import React from 'react';

const CrimeSceneIcon: React.FC<React.SVGProps<SVGSVGElement>> = (props) => (
  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth={1.5} stroke="currentColor" {...props}>
    <path strokeLinecap="round" strokeLinejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
  </svg>
);

export default CrimeSceneIcon;import React from 'react';

const FingerprintIcon: React.FC<React.SVGProps<SVGSVGElement>> = (props) => (
  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth={1.5} stroke="currentColor" {...props}>
    <path strokeLinecap="round" strokeLinejoin="round" d="M7.864 4.243A7.5 7.5 0 0119.5 10.5c0 2.92-.556 5.709-1.568 8.268M5.742 6.364A7.465 7.465 0 004.5 10.5a7.464 7.464 0 01-1.15 3.993m1.989 3.559A11.209 11.209 0 008.25 10.5a3.75 3.75 0 117.5 0c0 .527-.021 1.049-.064 1.565M12 10.5a14.94 14.94 0 01-3.6 9.75m6.633-4.596a18.666 18.666 0 01-2.485 5.33" />
  </svg>
);

export default FingerprintIcon;
import React from 'react';

const Footer: React.FC = () => {
  return (
    <footer className="bg-brand-primary text-brand-light text-center p-4 mt-auto">
      <p>&copy; {new Date().getFullYear()} Forensic Toolkit. All rights reserved.</p>
      <p className="text-xs mt-1">Simulated tools for demonstration purposes.</p>
    </footer>
  );
};

export default Footer;
