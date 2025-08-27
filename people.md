---
layout: page
title: People
---

<style>
.people-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

.section-header {
    text-align: center;
    margin: 40px 0 30px 0;
    position: relative;
}

.section-header h2 {
    font-size: 2.5rem;
    font-weight: 700;
    color: #2c3e50;
    margin-bottom: 10px;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
}

.section-header::after {
    content: '';
    position: absolute;
    bottom: -10px;
    left: 50%;
    transform: translateX(-50%);
    width: 80px;
    height: 4px;
    background: linear-gradient(90deg, #3498db, #e74c3c, #f39c12);
    border-radius: 2px;
}

.collaborators-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 25px;
    margin-bottom: 50px;
}

.collaborator-card {
    background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%);
    border-radius: 15px;
    padding: 25px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    transition: all 0.3s ease;
    border: 1px solid #e9ecef;
    position: relative;
    overflow: hidden;
}

.collaborator-card::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 4px;
    background: linear-gradient(90deg, #3498db, #e74c3c);
}

.collaborator-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 20px 40px rgba(0,0,0,0.15);
}

.collaborator-name {
    font-size: 1.3rem;
    font-weight: 600;
    color: #2c3e50;
    margin-bottom: 8px;
    display: flex;
    align-items: center;
    gap: 10px;
}

.collaborator-title {
    color: #7f8c8d;
    font-size: 1rem;
    margin-bottom: 5px;
    font-style: italic;
}

.collaborator-institution {
    color: #34495e;
    font-weight: 500;
    font-size: 0.95rem;
}

.mentorship-section {
    background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
    border-radius: 20px;
    padding: 30px;
    margin-bottom: 30px;
}

.mentorship-header {
    display: flex;
    align-items: center;
    gap: 15px;
    margin-bottom: 25px;
    padding-bottom: 15px;
    border-bottom: 2px solid #dee2e6;
}

.mentorship-title {
    font-size: 1.5rem;
    font-weight: 600;
    color: #2c3e50;
    margin: 0;
}

.mentorship-members {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 15px;
    margin-top: 20px;
}

.member-card {
    background: white;
    border-radius: 10px;
    padding: 15px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.08);
    transition: all 0.3s ease;
    border-left: 4px solid #3498db;
}

.member-card:hover {
    transform: translateX(5px);
    box-shadow: 0 8px 25px rgba(0,0,0,0.12);
}

.member-name {
    font-weight: 600;
    color: #2c3e50;
    margin-bottom: 5px;
}

.member-role {
    color: #7f8c8d;
    font-size: 0.9rem;
    font-style: italic;
}

.individual-mentorship {
    background: white;
    border-radius: 15px;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 8px 25px rgba(0,0,0,0.1);
    transition: all 0.3s ease;
    border-left: 5px solid #e74c3c;
}

.individual-mentorship:hover {
    transform: translateY(-3px);
    box-shadow: 0 15px 35px rgba(0,0,0,0.15);
}

.individual-header {
    display: flex;
    align-items: center;
    gap: 12px;
    margin-bottom: 10px;
}

.individual-name {
    font-size: 1.2rem;
    font-weight: 600;
    color: #2c3e50;
    margin: 0;
}

.individual-focus {
    color: #7f8c8d;
    font-size: 0.95rem;
    font-style: italic;
}

@media (max-width: 768px) {
    .collaborators-grid {
        grid-template-columns: 1fr;
    }
    
    .mentorship-members {
        grid-template-columns: 1fr;
    }
    
    .section-header h2 {
        font-size: 2rem;
    }
}
</style>

<div class="people-container">
    <div class="section-header">
        <h2>🤝 Collaborators</h2>
    </div>
    
    <div class="collaborators-grid">
        <div class="collaborator-card">
            <div class="collaborator-name">
                <span>👨‍🏫</span>
                <a href="https://www.stevens.edu/profile/syu19" target="_blank">Prof. Shucheng Yu</a>
            </div>
            <div class="collaborator-title">Associate Professor</div>
            <div class="collaborator-institution">Yeshiva University</div>
        </div>
        
        <div class="collaborator-card">
            <div class="collaborator-name">
                <span>👨‍🏫</span>
                <a href="https://www.stevens.edu/profile/msong6" target="_blank">Prof. Min Song</a>
            </div>
            <div class="collaborator-title">Professor</div>
            <div class="collaborator-institution">Stevens Institute of Technology</div>
        </div>
        
        <div class="collaborator-card">
            <div class="collaborator-name">
                <span>👩‍🏫</span>
                <a href="https://faculty.erau.edu/Laxima.NiureKandel" target="_blank">Prof. Laxima Niure Kandel</a>
            </div>
            <div class="collaborator-title">Assistant Professor</div>
            <div class="collaborator-institution">Embry-Riddle Aeronautical University</div>
        </div>
        
        <div class="collaborator-card">
            <div class="collaborator-name">
                <span>👨‍🏫</span>
                <a href="https://scholar.google.com/citations?user=v9zFuDEAAAAJ&hl=en" target="_blank">Prof. Yulong Zou</a>
            </div>
            <div class="collaborator-title">Professor</div>
            <div class="collaborator-institution">Nanjing University of Posts and Telecommunications</div>
        </div>
        
        <div class="collaborator-card">
            <div class="collaborator-name">
                <span>👨‍🏫</span>
                <a href="https://www.stevens.edu/profile/hli" target="_blank">Prof. Hongbin Li</a>
            </div>
            <div class="collaborator-title">Professor</div>
            <div class="collaborator-institution">Stevens Institute of Technology</div>
        </div>
        
        <div class="collaborator-card">
            <div class="collaborator-name">
                <span>👩‍🏫</span>
                <a href="https://www.stevens.edu/profile/ksubbala" target="_blank">Prof. K.P. (Suba) Subbalakshmi</a>
            </div>
            <div class="collaborator-title">Professor</div>
            <div class="collaborator-institution">Stevens Institute of Technology</div>
        </div>
        
        <div class="collaborator-card">
            <div class="collaborator-name">
                <span>👩‍🏫</span>
                <a href="https://www.stevens.edu/profile/ywang6" target="_blank">Prof. Ying Wang</a>
            </div>
            <div class="collaborator-title">Associate Professor</div>
            <div class="collaborator-institution">Stevens Institute of Technology</div>
        </div>
        
        <div class="collaborator-card">
            <div class="collaborator-name">
                <span>👨‍🏫</span>
                <a href="https://www2.hawaii.edu/~yaozheng/" target="_blank">Prof. Yao Zheng</a>
            </div>
            <div class="collaborator-title">Associate Professor</div>
            <div class="collaborator-institution">University of Hawaii at Mānoa</div>
        </div>
        
        <div class="collaborator-card">
            <div class="collaborator-name">
                <span>👨‍🏫</span>
                <span>Prof. Moh Khalid Hasan</span>
            </div>
            <div class="collaborator-title">Assistant Professor</div>
            <div class="collaborator-institution">James Madison University</div>
        </div>
    </div>
    
    <div class="section-header">
        <h2>🎓 Mentorships</h2>
    </div>
    
    <div class="mentorship-section">
        <div class="mentorship-header">
            <span style="font-size: 2rem;">🏆</span>
            <h3 class="mentorship-title">
                <a href="https://wbi-innovates.zohobackstage.com/afrlsdr" target="_blank">2024-2025 AFRL Software Design Radio (SDR) Challenge</a>
            </h3>
        </div>
        
        <div class="mentorship-members">
            <div class="member-card">
                <div class="member-name">Shaun George</div>
                <div class="member-role">Undergraduate Member</div>
            </div>
            <div class="member-card">
                <div class="member-name">Lenny Yanza</div>
                <div class="member-role">Undergraduate Member</div>
            </div>
            <div class="member-card">
                <div class="member-name">Karen Caguana</div>
                <div class="member-role">Undergraduate Member</div>
            </div>
            <div class="member-card">
                <div class="member-name">Xiangxi (Mall) Wang</div>
                <div class="member-role">Undergraduate Member</div>
            </div>
            <div class="member-card">
                <div class="member-name">Akshat Santhana Gopalan</div>
                <div class="member-role">High School Member</div>
            </div>
        </div>
    </div>
    
    <div class="individual-mentorship">
        <div class="individual-header">
            <span style="font-size: 1.5rem;">🎯</span>
            <h4 class="individual-name">
                <a href="https://srparkar.github.io/" target="_blank">Saurabh Raman Parkar</a>
            </h4>
        </div>
        <div class="individual-focus">Master, AI Integrated Sensing</div>
    </div>
    
    <div class="individual-mentorship">
        <div class="individual-header">
            <span style="font-size: 1.5rem;">🎯</span>
            <h4 class="individual-name">Ruoxi Li</h4>
        </div>
        <div class="individual-focus">Master, AI Integrated Sensing</div>
    </div>
    
    <div class="individual-mentorship">
        <div class="individual-header">
            <span style="font-size: 1.5rem;">🎯</span>
            <h4 class="individual-name">Beula Jose</h4>
        </div>
        <div class="individual-focus">Master, Wireless Security</div>
    </div>
    
    <div class="individual-mentorship">
        <div class="individual-header">
            <span style="font-size: 1.5rem;">🎯</span>
            <h4 class="individual-name">Zhifan Jiang</h4>
        </div>
        <div class="individual-focus">Master, SDR</div>
    </div>
    
    <div class="individual-mentorship">
        <div class="individual-header">
            <span style="font-size: 1.5rem;">🎯</span>
            <h4 class="individual-name">Jiapeng Xiao</h4>
        </div>
        <div class="individual-focus">Master, SDR</div>
    </div>
</div>