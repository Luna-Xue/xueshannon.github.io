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
    font-size: 3rem;
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

.collaborators-section {
    background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%);
    border-radius: 20px;
    padding: 40px;
    margin-bottom: 40px;
    box-shadow: 0 15px 35px rgba(0,0,0,0.1);
    border: 1px solid #e9ecef;
}

.mentorships-section {
    background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
    border-radius: 20px;
    padding: 40px;
    margin-bottom: 30px;
    box-shadow: 0 15px 35px rgba(0,0,0,0.1);
    border: 1px solid #dee2e6;
}

.phd-students-section {
    background: linear-gradient(135deg, #e8f5e8 0%, #d4edda 100%);
    border-radius: 20px;
    padding: 40px;
    margin-bottom: 30px;
    box-shadow: 0 15px 35px rgba(0,0,0,0.1);
    border: 1px solid #c3e6cb;
}

.collaborators-content {
    font-size: 1.4rem;
    line-height: 1.8;
    color: #2c3e50;
}

.collaborators-content h3 {
    font-size: 1.8rem;
    font-weight: 600;
    color: #34495e;
    margin-bottom: 20px;
    border-bottom: 2px solid #3498db;
    padding-bottom: 10px;
}

.collaborators-content ul {
    list-style: none;
    padding: 0;
}

.collaborators-content li {
    margin-bottom: 15px;
    padding: 15px;
    background: white;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.08);
    border-left: 4px solid #3498db;
    transition: all 0.3s ease;
}

.collaborators-content li:hover {
    transform: translateX(5px);
    box-shadow: 0 8px 25px rgba(0,0,0,0.12);
}

.collaborators-content a {
    color: #2c3e50;
    text-decoration: none;
    font-weight: 600;
}

.collaborators-content a:hover {
    color: #3498db;
}

.mentorships-content {
    font-size: 1.4rem;
    line-height: 1.8;
    color: #2c3e50;
}

.mentorships-content h3 {
    font-size: 1.8rem;
    font-weight: 600;
    color: #34495e;
    margin-bottom: 20px;
    border-bottom: 2px solid #e74c3c;
    padding-bottom: 10px;
}

.mentorships-content h4 {
    font-size: 1.6rem;
    font-weight: 600;
    color: #2c3e50;
    margin: 25px 0 15px 0;
}

.mentorships-content h5 {
    font-size: 1.4rem;
    font-weight: 600;
    color: #34495e;
    margin: 20px 0 10px 0;
    border-bottom: 1px solid #bdc3c7;
    padding-bottom: 5px;
}

.mentorships-content ul {
    list-style: none;
    padding: 0;
}

.mentorships-content li {
    margin-bottom: 15px;
    padding: 15px;
    background: white;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.08);
    border-left: 4px solid #e74c3c;
    transition: all 0.3s ease;
}

.mentorships-content li:hover {
    transform: translateX(5px);
    box-shadow: 0 8px 25px rgba(0,0,0,0.12);
}

.mentorships-content a {
    color: #2c3e50;
    text-decoration: none;
    font-weight: 600;
}

.mentorships-content a:hover {
    color: #e74c3c;
}

@media (max-width: 768px) {
    .section-header h2 {
        font-size: 2.5rem;
    }
    
    .collaborators-content,
    .mentorships-content {
        font-size: 1.2rem;
    }
    
    .collaborators-content h3,
    .mentorships-content h3 {
        font-size: 1.6rem;
    }
    
    .mentorships-content h4 {
        font-size: 1.4rem;
    }
}
</style>

<div class="people-container">
    <div class="section-header">
        <h2>Ph.D. Students</h2>
    </div>
    
    <div class="phd-students-section">
        <div class="phd-students-content">
            <ul>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="Saurabh Raman Parkar" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">👨‍🎓</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">
                            <a href="https://srparkar.github.io/" target="_blank">Saurabh Raman Parkar</a>
                        </div>
                        <div class="profile-description">AI Integrated Sensing</div>
                    </div>
                </li>
            </ul>
        </div>
    </div>
    
    <div class="section-header">
        <h2>Collaborators</h2>
    </div>
    
    <div class="collaborators-section">
        <div class="collaborators-content">
            <h3>Research Collaborators</h3>
            <ul>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="Prof. Shucheng Yu" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">👨‍🏫</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">
                            <a href="https://www.yu.edu/katz/faculty#:~:text=Liyang%20Yan%27s%20Bio-,Shucheng%20Yu,-AI" target="_blank">Prof. Shucheng Yu</a>
                        </div>
                        <div class="profile-description">Associate Professor, Yeshiva University</div>
                    </div>
                </li>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="Prof. Min Song" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">👨‍🏫</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">
                            <a href="https://www.stevens.edu/profile/msong6" target="_blank">Prof. Min Song</a>
                        </div>
                        <div class="profile-description">Professor, Stevens Institute of Technology</div>
                    </div>
                </li>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="Prof. Laxima Niure Kandel" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">👩‍🏫</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">
                            <a href="https://faculty.erau.edu/Laxima.NiureKandel" target="_blank">Prof. Laxima Niure Kandel</a>
                        </div>
                        <div class="profile-description">Assistant Professor, Embry-Riddle Aeronautical University</div>
                    </div>
                </li>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="Prof. Yulong Zou" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">👨‍🏫</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">
                            <a href="https://scholar.google.com/citations?user=v9zFuDEAAAAJ&hl=en" target="_blank">Prof. Yulong Zou</a>
                        </div>
                        <div class="profile-description">Professor, Nanjing University of Posts and Telecommunications</div>
                    </div>
                </li>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="Prof. Hongbin Li" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">👨‍🏫</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">
                            <a href="https://www.stevens.edu/profile/hli" target="_blank">Prof. Hongbin Li</a>
                        </div>
                        <div class="profile-description">Professor, Stevens Institute of Technology</div>
                    </div>
                </li>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="Prof. K.P. (Suba) Subbalakshmi" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">👩‍🏫</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">
                            <a href="https://www.stevens.edu/profile/ksubbala" target="_blank">Prof. K.P. (Suba) Subbalakshmi</a>
                        </div>
                        <div class="profile-description">Professor, Stevens Institute of Technology</div>
                    </div>
                </li>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="Prof. Ying Wang" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">👩‍🏫</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">
                            <a href="https://www.stevens.edu/profile/ywang6" target="_blank">Prof. Ying Wang</a>
                        </div>
                        <div class="profile-description">Associate Professor, Stevens Institute of Technology</div>
                    </div>
                </li>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="Prof. Yao Zheng" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">👨‍🏫</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">
                            <a href="https://www2.hawaii.edu/~yaozheng/" target="_blank">Prof. Yao Zheng</a>
                        </div>
                        <div class="profile-description">Associate Professor, University of Hawaii at Mānoa</div>
                    </div>
                </li>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="Prof. Moh Khalid Hasan" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">👨‍🏫</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">Prof. Moh Khalid Hasan</div>
                        <div class="profile-description">Assistant Professor, James Madison University</div>
                    </div>
                </li>
            </ul>
        </div>
    </div>
    
    <div class="section-header">
        <h2>Mentorships</h2>
    </div>
    
    <div class="mentorships-section">
        <div class="mentorships-content">
            <h3>Current Projects</h3>
            <h4>Group Mentorship</h4>
            <ul>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="AFRL SDR Challenge" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">🏆</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">
                            <a href="https://wbi-innovates.zohobackstage.com/afrlsdr" target="_blank">AFRL Software Design Radio (SDR) Challenge 2024-2025</a>
                        </div>
                        <div class="profile-description">Group Project</div>
                    </div>
                </li>
            </ul>
            
            <h4>Individual Mentorship</h4>
            <ul>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="Ruoxi Li" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">👨‍🎓</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">Ruoxi Li</div>
                        <div class="profile-description">Master, AI Integrated Sensing</div>
                    </div>
                </li>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="Beula Jose" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">👩‍🎓</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">Beula Jose</div>
                        <div class="profile-description">Master, Wireless Security</div>
                    </div>
                </li>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="Zhifan Jiang" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">👨‍🎓</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">Zhifan Jiang</div>
                        <div class="profile-description">Master, SDR</div>
                    </div>
                </li>
                <li>
                    <div class="profile-avatar">
                        <img src="img/avatar-placeholder.jpg" alt="Jiapeng Xiao" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <span style="display: none;">👨‍🎓</span>
                    </div>
                    <div class="profile-info">
                        <div class="profile-name">Jiapeng Xiao</div>
                        <div class="profile-description">Master, SDR</div>
                    </div>
                </li>
            </ul>
        </div>
    </div>
</div>