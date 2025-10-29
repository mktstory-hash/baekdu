import React from "react";

export default function BaekduHallaSite() {
  return (
    <div className="min-h-screen bg-white text-gray-900">
      {/* Header */}
      <header className="sticky top-0 z-10 bg-white/80 backdrop-blur border-b">
        <div className="mx-auto max-w-6xl px-6 py-4 flex items-center justify-between">
          <div className="flex items-center gap-3">
            <div className="h-9 w-9 rounded-2xl bg-gray-900 text-white flex items-center justify-center font-bold">BH</div>
            <h1 className="text-xl sm:text-2xl font-semibold">사단법인 백두한라협회</h1>
          </div>
          <nav className="hidden md:flex gap-6 text-sm">
            <a href="#about" className="hover:underline">협회 소개</a>
            <a href="#mission" className="hover:underline">설립취지·목적</a>
            <a href="#programs" className="hover:underline">주요 사업</a>
            <a href="#news" className="hover:underline">소식</a>
            <a href="#contact" className="hover:underline">연락처</a>
          </nav>
        </div>
      </header>

      {/* Hero */}
      <section className="bg-gradient-to-b from-gray-50 to-white">
        <div className="mx-auto max-w-6xl px-6 py-16 sm:py-24 grid md:grid-cols-2 gap-10 items-center">
          <div>
            <h2 className="text-3xl sm:text-4xl font-bold leading-tight">
              새터민과 지역사회가 함께 여는 <span className="bg-gray-900 text-white px-2 py-1 rounded-xl">자립·화합</span>
            </h2>
            <p className="mt-5 text-base sm:text-lg text-gray-600">
              백두에서 한라까지, 남과 북을 잇는 교량(橋梁)으로서 북한이탈주민의 자립과 역량강화,
              지역사회 참여와 화합을 촉진합니다.
            </p>
            <div className="mt-8 flex gap-3">
              <a href="#mission" className="px-4 py-2 rounded-2xl bg-gray-900 text-white text-sm">설립취지 보기</a>
              <a href="#programs" className="px-4 py-2 rounded-2xl border text-sm">사업 살펴보기</a>
            </div>
            <div className="mt-4 text-xs text-gray-500">
              공식 홈페이지: {" "}
              <a className="underline" href="https://www.xn--hu1b53di9enx5a5zadv.org/" target="_blank" rel="noreferrer">
                백두한라협회.org
              </a>
            </div>
          </div>
          <div className="p-4">
            <div className="rounded-2xl border bg-white p-6 shadow-sm">
              <h3 className="font-semibold text-lg">핵심 가치</h3>
              <ul className="mt-4 grid sm:grid-cols-2 gap-3 text-sm">
                <li className="p-3 rounded-xl bg-gray-50 border">자립(IL) 촉진</li>
                <li className="p-3 rounded-xl bg-gray-50 border">권익옹호</li>
                <li className="p-3 rounded-xl bg-gray-50 border">역량강화</li>
                <li className="p-3 rounded-xl bg-gray-50 border">지역사회 화합</li>
              </ul>
            </div>
          </div>
        </div>
      </section>

      {/* About */}
      <section id="about" className="mx-auto max-w-6xl px-6 py-16 border-t">
        <div className="grid md:grid-cols-3 gap-10">
          <div className="md:col-span-2">
            <h3 className="text-2xl font-semibold">협회 소개</h3>
            <p className="mt-4 text-gray-700 leading-relaxed">
              (사)백두한라협회는 2007년에 설립되어 북한이탈주민(새터민)이 지역사회에서 자립적으로
              생활하고 당당한 시민으로 성장할 수 있도록 지원하는 비영리 민간단체입니다. 협회는 교육·상담·문화·
              일자리 연계 등 다양한 프로그램을 통해 당사자 역량을 높이고, 지역사회의 이해와 참여를 확대합니다.
            </p>
          </div>
          <aside className="md:col-span-1">
            <div className="rounded-2xl border bg-gray-50 p-5">
              <div className="text-sm text-gray-600">최근 활동 스냅샷</div>
              <ul className="mt-3 text-sm list-disc pl-5 space-y-2">
                <li>정기 급식 및 공연봉사 진행</li>
                <li>지역 기업·기관과 협력 MOU 체결</li>
                <li>백두한라예술단 지역 축제 공연 참여</li>
              </ul>
            </div>
          </aside>
        </div>
      </section>

      {/* Mission */}
      <section id="mission" className="mx-auto max-w-6xl px-6 py-16 border-t">
        <h3 className="text-2xl font-semibold">설립취지·목적</h3>
        <div className="mt-4 grid md:grid-cols-2 gap-8">
          <div className="rounded-2xl border p-6">
            <p className="text-gray-700 leading-relaxed">
              북한이탈주민이 지역사회에 주체적으로 참여하고 자립적으로 생활할 수 있도록 돕기 위해 설립되었습니다.
              차별적 구조를 변화시키고, 당사자의 역량강화와 사회통합에 기여합니다.
            </p>
          </div>
          <div className="rounded-2xl border p-6">
            <ul className="grid gap-3 text-sm">
              <li className="p-3 rounded-xl bg-gray-50 border">자립생활(IL) 이념 보급</li>
              <li className="p-3 rounded-xl bg-gray-50 border">새터민 권익옹호 및 사회참여 촉진</li>
              <li className="p-3 rounded-xl bg-gray-50 border">당사자 리더십 및 시민역량 강화</li>
            </ul>
          </div>
        </div>
      </section>

      {/* Programs */}
      <section id="programs" className="mx-auto max-w-6xl px-6 py-16 border-t">
        <h3 className="text-2xl font-semibold">주요 사업</h3>
        <div className="mt-6 grid md:grid-cols-2 xl:grid-cols-3 gap-6">
          {[
            {
              title: "자립생활기술(IL) 교육",
              desc: "동료상담·생활기술·권리교육 등 맞춤형 커리큘럼으로 실질적 자립역량을 강화합니다.",
            },
            {
              title: "동료상담가 양성/파견",
              desc: "당사자 중심의 동료상담가를 교육하고 지역 사회복지기관 등에 파견합니다.",
            },
            {
              title: "권익옹호·정책 제안",
              desc: "생활·고용·교육·문화 접근성 개선을 위한 캠페인과 정책제안을 진행합니다.",
            },
            {
              title: "문화·예술단 운영",
              desc: "백두한라예술단 운영으로 주민과 함께하는 공연·축제 참여 및 지역 화합을 도모합니다.",
            },
            {
              title: "취업·창업 연계",
              desc: "지역 기업과의 MOU를 바탕으로 일경험, 일자리 연계, 기부·후원 네트워크를 확장합니다.",
            },
            {
              title: "지역 봉사·나눔",
              desc: "정기 급식 봉사, 생활물품 지원 등 지역사회 나눔 활동을 수행합니다.",
            },
          ].map((p, i) => (
            <div key={i} className="rounded-2xl border p-6 bg-white">
              <h4 className="font-semibold">{p.title}</h4>
              <p className="mt-2 text-sm text-gray-700">{p.desc}</p>
            </div>
          ))}
        </div>
      </section>

      {/* News */}
      <section id="news" className="mx-auto max-w-6xl px-6 py-16 border-t">
        <h3 className="text-2xl font-semibold">소식</h3>
        <div className="mt-6 grid md:grid-cols-2 gap-6">
          <article className="rounded-2xl border p-6 bg-white">
            <div className="text-xs text-gray-500">최근</div>
            <h4 className="mt-1 font-semibold">LG전자 대전 둔산점과 업무협약</h4>
            <p className="mt-2 text-sm text-gray-700">북한이탈주민 지원사업 협력을 위한 지역 기업 파트너십을 체결했습니다.</p>
            <a className="mt-3 inline-block text-sm underline" href="https://www.nexttimes.kr/news/articleView.html?idxno=4005" target="_blank" rel="noreferrer">보도자료 보기</a>
          </article>
          <article className="rounded-2xl border p-6 bg-white">
            <div className="text-xs text-gray-500">최근</div>
            <h4 className="mt-1 font-semibold">지역 축제 참여 — 백두한라예술단</h4>
            <p className="mt-2 text-sm text-gray-700">시민과 함께하는 노래자랑 등 지역 문화행사에 참여했습니다.</p>
            <a className="mt-3 inline-block text-sm underline" href="https://www.youtube.com/watch?v=Mdolc4gcXDc" target="_blank" rel="noreferrer">영상 보기</a>
          </article>
        </div>
      </section>

      {/* Contact */}
      <section id="contact" className="mx-auto max-w-6xl px-6 py-16 border-t">
        <h3 className="text-2xl font-semibold">연락처</h3>
        <div className="mt-4 grid md:grid-cols-2 gap-8">
          <div className="rounded-2xl border p-6 bg-white">
            <p className="text-sm text-gray-700">
              이메일: <span className="font-medium">info@baekduhalla.org</span> (예시)<br/>
              주소: 대전광역시 (예시 — 실제 주소 입력)
            </p>
            <p className="mt-3 text-xs text-gray-500">※ 실제 연락처·주소는 확인 후 업데이트하세요.</p>
          </div>
          <form className="rounded-2xl border p-6 bg-white">
            <label className="text-sm">문의하기</label>
            <input className="mt-2 w-full border rounded-xl p-3" placeholder="이름"/>
            <input className="mt-2 w-full border rounded-xl p-3" placeholder="이메일"/>
            <textarea className="mt-2 w-full border rounded-xl p-3 h-28" placeholder="문의 내용"/>
            <button type="button" className="mt-3 px-4 py-2 rounded-2xl bg-gray-900 text-white text-sm">문의 접수</button>
            <p className="mt-2 text-xs text-gray-500">* 데모 폼 — 백엔드 연동 필요</p>
          </form>
        </div>
      </section>

      {/* Footer */}
      <footer className="border-t">
        <div className="mx-auto max-w-6xl px-6 py-10 text-sm text-gray-600">
          © {new Date().getFullYear()} 사단법인 백두한라협회 · Baekdu–Halla Association
        </div>
      </footer>
    </div>
  );
}
