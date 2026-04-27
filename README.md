# HydroHackathon Indian Institute of Technology (IIT), Madras

https://unstop.com/hackathons/hydrohackathon-iit-madras-1677701

import { Lightbulb } from 'lucide-react';

export default function App() {
  return (
    <div className="min-h-screen bg-gray-100">
      {/* Header */}
      <div className="bg-white border-b border-gray-200 px-6 py-4 flex items-center gap-4">
        <img
          src="https://csspicker.dev/api/image/?q=IIT+Madras+logo&image_type=vector"
          alt="IIT Madras Logo"
          className="w-12 h-12 rounded-full object-cover"
        />
        <div>
          <h1 className="text-xl font-semibold text-gray-800">HydroHackathon</h1>
          <p className="text-sm text-gray-500">Indian Institute of Technology (IIT), Madras</p>
        </div>
      </div>

      {/* Blue divider line */}
      <div className="h-0.5 bg-blue-500 w-full" />

      {/* Main Content */}
      <div className="bg-white min-h-screen px-8 pt-6">
        <div className="flex items-start justify-between">
          {/* My Team Tab */}
          <div className="relative">
            <span className="text-blue-600 font-semibold text-base pb-2 block">My Team</span>
            <div className="absolute bottom-0 left-0 w-full h-0.5 bg-blue-600" />
          </div>

          {/* Lightbulb icon button */}
          <button className="border border-dashed border-yellow-400 rounded-md p-2 text-yellow-500 hover:bg-yellow-50 transition-colors">
            <Lightbulb className="w-5 h-5" />
          </button>
        </div>

        {/* Divider below tab */}
        <div className="border-b border-gray-200 mb-8" />

        {/* Team Name */}
        <div className="flex items-center gap-4 mb-8">
          <span className="text-gray-700 font-medium text-base">Team Name</span>
          <span className="text-gray-400 text-base">Pankajanghri</span>
        </div>

        {/* Team Member Card */}
        <div className="bg-green-50 border-l-4 border-green-500 rounded-md flex items-center px-4 py-3 gap-4 max-w-3xl">
          <div className="w-10 h-10 rounded-full bg-green-200 flex items-center justify-center text-green-700 font-bold text-sm flex-shrink-0">
            S
          </div>
          <span className="text-gray-800 font-semibold text-sm tracking-wide">SHREYAS MISHRA</span>
        </div>
      </div>
    </div>
  );
}


