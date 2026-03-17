  DirectX 11 기반의 경량화된 C++ 게임 엔진 및 에디터 프로젝트입니다.

  🚀 Key Features

  1. Core Architecture
   - Object System: RTTI(Runtime Type Information)와 리플렉션을 지원하는 커스텀 오브젝트 시스템 (UObject, Cast<T>).
   - Component-Based: USceneComponent를 기반으로 하는 유연한 컴포넌트 구조.
   - Serialization: JSON 기반의 씬(Scene) 저장 및 로드 시스템.

  2. Rendering (DirectX 11)
   - D3D11 Pipeline: Vertex/Pixel Shader 기반의 렌더링 파이프라인.
   - Primitive Components: Cube, Sphere, Triangle, Plane 등 기본 기하 구조 지원.
   - Infinite Grid: 동적 카메라 거리에 반응하는 무한 그리드 렌더링.
   - Constant Buffer Management: View/Proj/World 행렬 및 오브젝트 속성 관리.

  3. Integrated Editor (ImGui)
   - Scene Hierarchy & Property Panel: 오브젝트 계층 구조 및 속성 실시간 편집.
   - Gizmo System: Translation, Rotation, Scale 조작을 위한 3D 기즈모 및 피킹(Picking) 시스템.
   - Console & Stat Panel: 엔진 로그 출력 및 프레임워크 성능 모니터링.

  4. Math Library
   - 자체 구현된 Vector, Matrix, Quaternion 클래스를 통한 3D 연산 지원.

  🛠 Tech Stack
   - Language: C++
   - Graphics API: DirectX 11
   - UI Framework: Dear ImGui
   - OS: Windows (Win32 API)
   - Build Tool: Visual Studio 2022

  📂 Project Structure
   - CustomGameEngine/: 엔진 핵심 로직 및 프레임워크
   - Component/: 카메라, 메시, 축 등 각종 컴포넌트
   - Editor/: 기즈모 및 에디터 UI 시스템
   - Renderer/: D3D11 렌더러 및 리소스 관리
