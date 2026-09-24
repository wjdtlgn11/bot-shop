'use client';
import { useState } from 'react';

export default function Home() {
  const [isAdmin, setIsAdmin] = useState(false);
  const [bots, setBots] = useState([
    { 
      id: 1, 
      title: '⚡ 디스코드 셀프봇 (소스코드 지원)', 
      price: '35,000원', 
      desc: '다양한 명령어와 유틸리티를 지원하는 고성능 셀프봇 소스코드 패키지',
      features: [
        '!테러', '!니트로폭격(ip)', '!도배', '!사칭도배 [@유저] [할말]', 
        '!가짜공지', '!디엠', '!역할폭격', '!역할삭제', '!채널도배', 
        '!벤폭격', '!닉네임테러', '!이모지테러', '!서버정보변경', '!서버정보', 
        '!유저정보 [@유저]', '!관리자검사', '!스니핑', '!채팅랭킹', 
        '!통계', '!유저추적', '!서버복사 등등'
      ]
    },
    { 
      id: 2, 
      title: '💥 디스코드 서버테러봇 (소스코드 지원)', 
      price: '20,000원', 
      desc: '서버테러 및 대규모 레이드 제어 기능, 채널/역할 일괄 생성/삭제 시스템, 웹훅 및 스팸 메시지 폭격 시스템, 빠르고 안정적인 구동 소스코드 제공',
      features: [
        '서버테러 및 레이드 제어', 
        '채널/역할 일괄 생성 및 삭제', 
        '웹훅 및 스팸 메시지 폭격', 
        '안정적인 구동 소스코드 제공'
      ]
    }
  ]);

  // 관리자 모드 비밀번호 로그인 (비번: 1203)
  const handleAdminLogin = () => {
    const pw = prompt("관리자 비밀번호를 입력하세요:");
    if (pw === "1203") {
      setIsAdmin(true);
      alert("👑 관리자 모드가 활성화되었습니다!");
    } else {
      alert("❌ 비밀번호가 틀렸습니다.");
    }
  };

  return (
    <div style={{ minHeight: '100vh', background: '#090d16', color: '#ffffff', fontFamily: 'sans-serif', padding: '40px 20px' }}>
      <div style={{ maxWidth: '900px', margin: '0 auto' }}>
        
        {/* 상단 헤더 */}
        <div style={{ display: 'flex', justifyContent: 'space-between', alignItems: 'center', marginBottom: '40px', borderBottom: '1px solid #1e293b', paddingBottom: '20px' }}>
          <div>
            <h1 style={{ fontSize: '24px', margin: 0, fontWeight: 'bold' }}>🤖 디스코드 봇 & 소스코드 마켓</h1>
            <p style={{ color: '#94a3b8', fontSize: '14px', margin: '5px 0 0 0' }}>안전하고 빠른 디스코드 봇 분양</p>
          </div>
          <button 
            onClick={handleAdminLogin}
            style={{ background: isAdmin ? '#10b981' : '#1e293b', color: '#fff', border: '1px solid #334155', padding: '8px 16px', borderRadius: '8px', cursor: 'pointer', fontWeight: 'bold' }}
          >
            {isAdmin ? "👑 관리자 작동중" : "관리자 로그인"}
          </button>
        </div>

        {/* 관리자일 때만 보이는 새 봇 등록 패널 */}
        {isAdmin && (
          <div style={{ background: '#111827', border: '1px solid #3b82f6', padding: '24px', borderRadius: '12px', marginBottom: '40px' }}>
            <h3 style={{ margin: '0 0 15px 0', color: '#60a5fa' }}>🛠️ [관리자] 새로운 봇 등록하기</h3>
            <form onSubmit={(e) => {
              e.preventDefault();
              const form = e.currentTarget;
              const newBot = {
                id: Date.now(),
                title: form.botTitle.value,
                price: form.botPrice.value,
                desc: form.botDesc.value,
                features: form.botFeatures.value.split(',')
              };
              setBots([newBot, ...bots]);
              form.reset();
              alert("성공적으로 등록되었습니다!");
            }}>
              <div style={{ marginBottom: '12px' }}>
                <input name="botTitle" placeholder="봇 이름 (예: 특수 봇 (소스코드 지원))" style={{ width: '100%', padding: '10px', background: '#1f2937', border: '1px solid #374151', color: '#fff', borderRadius: '6px' }} required />
              </div>
              <div style={{ marginBottom: '12px' }}>
                <input name="botPrice" placeholder="가격 (예: 10,000원)" style={{ width: '100%', padding: '10px', background: '#1f2937', border: '1px solid #374151', color: '#fff', borderRadius: '6px' }} required />
              </div>
              <div style={{ marginBottom: '12px' }}>
                <input name="botDesc" placeholder="짧은 설명" style={{ width: '100%', padding: '10px', background: '#1f2937', border: '1px solid #374151', color: '#fff', borderRadius: '6px' }} required />
              </div>
              <div style={{ marginBottom: '12px' }}>
                <textarea name="botFeatures" placeholder="기능들을 콤마(,)로 구분해서 입력해주세요" style={{ width: '100%', padding: '10px', background: '#1f2937', border: '1px solid #374151', color: '#fff', borderRadius: '6px', height: '60px' }} required />
              </div>
              <button type="submit" style={{ background: '#3b82f6', color: '#fff', border: 'none', padding: '10px 20px', borderRadius: '6px', fontWeight: 'bold', cursor: 'pointer' }}>
                스토어에 등록하기
              </button>
            </form>
          </div>
        )}

        {/* 봇 상품 리스트 그리드 */}
        <h2 style={{ fontSize: '20px', marginBottom: '20px' }}>📦 판매 중인 봇 목록</h2>
        <div style={{ display: 'grid', gridTemplateColumns: 'repeat(auto-fill, minmax(280px, 1fr))', gap: '20px' }}>
          {bots.map((bot) => (
            <div key={bot.id} style={{ background: '#111827', border: '1px solid #1f2937', borderRadius: '12px', padding: '20px', display: 'flex', flexDirection: 'column', justifyContent: 'space-between' }}>
              <div>
                <h3 style={{ margin: '0 0 10px 0', fontSize: '18px', color: '#f8fafc' }}>{bot.title}</h3>
                <p style={{ color: '#94a3b8', fontSize: '13px', lineHeight: '1.4', margin: '0 0 15px 0' }}>{bot.desc}</p>
                
                {/* 기능 목록 표시 박스 */}
                <div style={{ background: '#020617', padding: '12px', borderRadius: '8px', marginBottom: '15px', border: '1px solid #1e293b' }}>
                  <p style={{ fontSize: '12px', color: '#38bdf8', fontWeight: 'bold', margin: '0 0 8px 0' }}>📌 주요 기능 및 명령어:</p>
                  <div style={{ display: 'flex', flexWrap: 'wrap', gap: '5px' }}>
                    {bot.features.map((feat, idx) => (
                      <span key={idx} style={{ background: '#1e293b', color: '#cbd5e1', fontSize: '11px', padding: '3px 6px', borderRadius: '4px' }}>
                        {feat.trim()}
                      </span>
                    ))}
                  </div>
                </div>

                <div style={{ fontSize: '18px', fontWeight: 'bold', color: '#38bdf8', marginBottom: '15px' }}>{bot.price}</div>
              </div>

              {/* 구매 버튼 (누르면 내 디스코드 DM으로 연결) */}
              <a 
                href="https://discord.com/users/1531164394874994813" 
                target="_blank" 
                rel="noopener noreferrer"
                style={{ textAlign: 'center', background: '#5865F2', color: '#fff', padding: '10px', borderRadius: '8px', textDecoration: 'none', fontWeight: 'bold', fontSize: '14px' }}
              >
                💬 구매 및 문의하기
              </a>
            </div>
          ))}
        </div>

      </div>
    </div>
  );
}
