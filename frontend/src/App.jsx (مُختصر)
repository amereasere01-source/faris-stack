import { Canvas } from '@react-three/fiber';
import { OrbitControls, Stars } from '@react-three/drei';
import Dashboard from './scenes/Dashboard';
import { BrowserRouter, Routes, Route } from 'react-router-dom';
export default function App() {
  return (
    <BrowserRouter>
     <div className="min-h-screen bg-black text-cyan-300">
      <Canvas>
        <Stars radius={200} depth={50} count={5000}/>
        <OrbitControls enableZoom={false}/>
      </Canvas>
      <Routes>
        <Route path="/" element={<Dashboard/>}/>
      </Routes>
     </div>
    </BrowserRouter>
  );
}
